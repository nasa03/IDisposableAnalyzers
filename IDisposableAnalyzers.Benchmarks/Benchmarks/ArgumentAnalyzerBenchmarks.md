``` ini

BenchmarkDotNet=v0.10.13, OS=Windows 7 SP1 (6.1.7601.0)
Intel Xeon CPU E5-2637 v4 3.50GHz, 2 CPU, 16 logical cores and 8 physical cores
Frequency=3410117 Hz, Resolution=293.2451 ns, Timer=TSC
  [Host]     : .NET Framework 4.7.1 (CLR 4.0.30319.42000), 64bit RyuJIT-v4.7.2558.0
  DefaultJob : .NET Framework 4.7.1 (CLR 4.0.30319.42000), 64bit RyuJIT-v4.7.2558.0


```
|                    Method |     Mean |    Error |   StdDev |     Gen 0 |    Gen 1 | Allocated |
|-------------------------- |---------:|---------:|---------:|----------:|---------:|----------:|
| RunOnIDisposableAnalyzers | 671.7 ms | 13.18 ms | 26.33 ms | 5937.5000 | 187.5000 |  35.76 MB |