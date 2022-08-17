# SQL-Levels-Explained

explaining sql levels based on one meme:

<img src="https://user-images.githubusercontent.com/6764957/185188888-e06ef45b-c749-4f19-b918-1d3530f4f634.png" height=300 />

## Level 0

- Concepts
  - ORMs
  - data types
  - foreign keys
  - indexes
- SQL
  - SELECT/INSERT/UPDATE/DELETE
  - ORDER BY
  - GROUP BY
  - LIMIT/OFFSET
  - CREATE TABLE
  - JOIN


## Level 1

- Concepts
  - ACID
  - transactions
  - keyset pagination
  - normal forms
  - computed columns
  - stored columns
  - inverted indexes
  - window functions
- SQL
  - outer joins
  - ORDER BY in aggregates
  - CTEs
  - query plans and EXPLAIN

## Level 2

- Concepts
  - Connection pools
  - plan hints
  - cursors
  - MVCC garbage collection
  - recursive CTEs
  - LATERAL joins
- Insights
  - ORMs create bad queries: *explanation needed*
  - optimizers don't work without table statistics: *explanation needed*
  - there are no non-nullable types: *explanation needed*
  
## Level 3

- Concepts
  - MERGE
  - COUNT(*) vs COUNT(1)
  - isolation levels
  - zigzag join
  - grouping sets, cube, rollup
  - write skew
  - partial indexes
  - sharding
  - phantom reads
  - triggers
- Insights
  - serializable restarts require retry loops on all statements: *explanation needed*
  - generator functions zip when cross joined: *explanation needed*
  
## Level 4

- Concepts
  - SELECT FOR UPDATE
  - denormalization
  - transaction contention
  - sargability
  - star schemas
  - utf8mb4
- Insights
  - Ascending Key Problem: *explanation needed*
  - Ambiguous network errors: *explanation needed*
  - NULLs in CHECK constraints are truthy: *explanation needed*
  
## Level 5

- Concepts
  - DEFERRABLE INITIALLY IMMEDIATE
  - MATCH PARTIAL foreign keys
  - EXPLAIN approximates SELECT COUNT(*)
  - causual reverse
- Insights
  - TPCC requires wait times: *explanation needed*
  - cost models don't reflect reality: *explanation needed*
  - 'null'::jsonb IS NULL = false: *explanation needed*

## Level 6
  
- Concepts
  - database cracking: *explanation needed*
  - learned indexes: *explanation needed*
  - XTID exhaustion: *explanation needed*
  - Worst Case Optimal Join: *explanation needed*
  - Volcano model: *explanation needed*
- Battle Scars
  - Vectorized doesn't mean SIMD: *explanation needed*
  - join ordering is NP hard: *explanation needed*
  - NULLs are equal in DISTINCT but inequal in UNIQUE: *explanation needed*


## Level 7


- dee and dum: *explanation needed*
- the Halloween problem: *explanation needed*
- allballs: *explanation needed*
- fsyncgate: *explanation needed*
- Every SQL operator is actually a JOIN: *explanation needed*
- SERIAL is non-transactional: *explanation needed*
- NULL (?): *explanation needed*





