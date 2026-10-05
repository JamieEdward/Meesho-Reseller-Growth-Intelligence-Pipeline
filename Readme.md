# Meesho Reseller Growth Intelligence Pipeline

An integrated, production-ready analytics and agentic reporting pipeline designed to replace manual spreadsheet tracking for Meesho reseller operations. This system transforms raw transactional order data into deterministic growth metrics, applies strict data quality guardrails, masks personal reseller identities, and drafts factual stakeholder alerts subject to human approval. 

# 1. Generate Dataset & Seed SQLite DB
python data/generate_dataset.py

# 2. Execute SQL Business Queries & Export CSVs
python part1_sql/query.py

# 3. Execute Part 2 Growth Engine & Validation Unit Tests
python part2_engine/test_growth_engine.py

# 4. View Formatted MoM Growth Tables in Console
python part2_engine/print_table.py

# 5. Execute Part 3 Reseller Identity Masking Tests
python part3_narrative/masking.py

# 6. Execute Part 4 Mock Agent Pipeline Runner
python part4_agent/mock_agent_runner.py