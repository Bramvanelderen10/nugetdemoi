# Demo of problem with content files with a project that refers a nuget which refers a nuget with contentfiles which should go to output dir

The problem is:

In the Api project the base.json is included, however the path where it was located in the Base project is not maintained and also it does not copy to output directory
