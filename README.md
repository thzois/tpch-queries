# TPC-H Benchmark
The [TPC-H](http://www.tpc.org/tpch/) benchmark, is a decision support benchmark. It consists of a suite of business oriented ad-hoc queries and concurrent data modifications. The queries of the benchamark have broad industry-wide relevance and examine large volumes of data with a high degree of complexity. They are designed to give answers to critical business questions.

This repository contains the queries in the SQL standards supported by PostgreSQL and MariaDB.

### Query 11
For q11 there a constant `FRAQ` that needs to be adjusted according to the scale factor (SF): `FRAQ = 0.0001 / SF`
