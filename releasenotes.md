# Releasenotes
### 1.0.0
- Speedup: Using compiled Expressions instead of reflection for setting Oracle-specific properties
- Package icon and author changed to DIPS AS
- Using built-in packagereferences instead of paket(less hassle for such a small project)

### 0.9.9
- No changes except build system, moving to dotnet pack broke nuget package metadata
### 0.9.8
- Multitarget build for both .net452 and .netstandard2.0
### 0.9.7
- Added Status to OracleParameter, this is returned by some stored procs.
### 0.9.6
- Added ArrayBindSize property to OracleParameter, can now set this property on OracleCommand for both managed and unmanaged driver.
### 0.9.5
- Made OracleDynamicParameters.AddParameters virtual, so that it can be extended in a derived class.
### 0.9.0
- Initial commit to Github.