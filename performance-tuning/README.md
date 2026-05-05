# MySQL Performance Tuning

## Objective
To improve query performance using indexing.

## Slow Query Example
SELECT * FROM users WHERE name='Ali';

## Optimization
CREATE INDEX idx_name ON users(name);

## Result
Query execution time improved after indexing.
