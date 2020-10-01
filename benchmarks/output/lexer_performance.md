# Benchmark

Benchmark run from 2020-10-01 18:18:23.961056Z UTC

## System

Benchmark suite executing on the following system:

<table style="width: 1%">
  <tr>
    <th style="width: 1%; white-space: nowrap">Operating System</th>
    <td>Linux</td>
  </tr><tr>
    <th style="white-space: nowrap">CPU Information</th>
    <td style="white-space: nowrap">Intel(R) Core(TM) i7-6700HQ CPU @ 2.60GHz</td>
  </tr><tr>
    <th style="white-space: nowrap">Number of Available Cores</th>
    <td style="white-space: nowrap">8</td>
  </tr><tr>
    <th style="white-space: nowrap">Available Memory</th>
    <td style="white-space: nowrap">7.87 GB</td>
  </tr><tr>
    <th style="white-space: nowrap">Elixir Version</th>
    <td style="white-space: nowrap">1.10.4</td>
  </tr><tr>
    <th style="white-space: nowrap">Erlang Version</th>
    <td style="white-space: nowrap">23.0.3</td>
  </tr>
</table>

## Configuration

Benchmark suite executing with the following configuration:

<table style="width: 1%">
  <tr>
    <th style="width: 1%">:time</th>
    <td style="white-space: nowrap">5 s</td>
  </tr><tr>
    <th>:parallel</th>
    <td style="white-space: nowrap">1</td>
  </tr><tr>
    <th>:warmup</th>
    <td style="white-space: nowrap">2 s</td>
  </tr>
</table>

## Statistics

Run Time
<table style="width: 1%">
  <tr>
    <th>Name</th>
    <th style="text-align: right">IPS</th>
    <th style="text-align: right">Average</th>
    <th style="text-align: right">Devitation</th>
    <th style="text-align: right">Median</th>
    <th style="text-align: right">99th&nbsp;%</th>
  </tr>
  <tr>
    <td style="white-space: nowrap">Lexer performance - ascii only</td>
    <td style="white-space: nowrap; text-align: right">54.07</td>
    <td style="white-space: nowrap; text-align: right">18.49 ms</td>
    <td style="white-space: nowrap; text-align: right">±16.44%</td>
    <td style="white-space: nowrap; text-align: right">17.81 ms</td>
    <td style="white-space: nowrap; text-align: right">32.91 ms</td>
  </tr>
  <tr>
    <td style="white-space: nowrap">Lexer performance - custom parsec</td>
    <td style="white-space: nowrap; text-align: right">37.74</td>
    <td style="white-space: nowrap; text-align: right">26.50 ms</td>
    <td style="white-space: nowrap; text-align: right">±26.80%</td>
    <td style="white-space: nowrap; text-align: right">24.15 ms</td>
    <td style="white-space: nowrap; text-align: right">41.61 ms</td>
  </tr>
  <tr>
    <td style="white-space: nowrap">Lexer performance - parsec</td>
    <td style="white-space: nowrap; text-align: right">32.66</td>
    <td style="white-space: nowrap; text-align: right">30.62 ms</td>
    <td style="white-space: nowrap; text-align: right">±23.54%</td>
    <td style="white-space: nowrap; text-align: right">31.11 ms</td>
    <td style="white-space: nowrap; text-align: right">62.52 ms</td>
  </tr>
  <tr>
    <td style="white-space: nowrap">Lexer performance - custom parsec 2</td>
    <td style="white-space: nowrap; text-align: right">32.59</td>
    <td style="white-space: nowrap; text-align: right">30.68 ms</td>
    <td style="white-space: nowrap; text-align: right">±39.14%</td>
    <td style="white-space: nowrap; text-align: right">26.13 ms</td>
    <td style="white-space: nowrap; text-align: right">60.93 ms</td>
  </tr>
</table>
Comparison
<table style="width: 1%">
  <tr>
    <th>Name</th>
    <th style="text-align: right">IPS</th>
    <th style="text-align: right">Slower</th>
  <tr>
    <td style="white-space: nowrap">Lexer performance - ascii only</td>
    <td style="white-space: nowrap;text-align: right">54.07</td>
    <td>&nbsp;</td>
  </tr>
  <tr>
    <td style="white-space: nowrap">Lexer performance - custom parsec</td>
    <td style="white-space: nowrap; text-align: right">37.74</td>
    <td style="white-space: nowrap; text-align: right">1.43x</td>
  </tr>
  <tr>
    <td style="white-space: nowrap">Lexer performance - parsec</td>
    <td style="white-space: nowrap; text-align: right">32.66</td>
    <td style="white-space: nowrap; text-align: right">1.66x</td>
  </tr>
  <tr>
    <td style="white-space: nowrap">Lexer performance - custom parsec 2</td>
    <td style="white-space: nowrap; text-align: right">32.59</td>
    <td style="white-space: nowrap; text-align: right">1.66x</td>
  </tr>
</table>
<hr/>