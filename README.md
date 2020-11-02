# Comp-CIT496CloudBenchmarks

These Benchmarks are designated to test EC2/ECS, Litespeed, & NginX servers with Apache Benchmarks.

Benchmark 1:
  Outputs "Hello World"
  
Benchmark 2:
  Outputs no-op (echo "";)
  
Benchmark 3:
  ENV - prints out all CGI environment variables in a LOOP
  
Benchmark 4:
  Echo Request variables in a LOOP passed via HTML - (http://localhost/newid.php?name=shareonthelove&job=student)
  
Benchmark 5:
  ENV - prints out all CGI environment variables with var_dump
  
Benchmark 6:
  Echo Request variables with var_dump passed via HTML - (http://localhost/newid.php?name=shareonthelove&job=student)
  
Benchmark 7:
  Professor's newid.php - must have access to professor's "cloudproject" database (mysql)
