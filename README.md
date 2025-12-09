# NEBA Smart Contracts

Solana-based smart contracts for the NEBA Protocol AI-adaptive reward system.

## Status

🚧 **Under Development** - Testnet deployment planned Q2 2026

## Architecture

### Core Contracts

- **Token Program**: SPL Token implementation with custom extensions
- **Reward Engine**: Epoch-based distribution logic with circuit breakers
- **Oracle Validator**: Optimistic verification and fraud proof handling
- **Governance Module**: Time-locked parameter adjustments
- **Emergency Controls**: Multi-signature pause mechanisms

### Security Features

- Hard-coded monthly emission caps
- Statistical anomaly detection
- ±20% epoch variance limits
- Multi-signature emergency controls
- Stake-slashing for oracle fraud

## Technical Stack

- **Language**: Rust
- **Framework**: Anchor Framework
- **Blockchain**: Solana
- **Token Standard**: SPL Token (with custom program)
- **Testing**: Solana Test Validator + TypeScript integration tests

## Project Structure
```
neba-contracts/
├── programs/
│   ├── neba-token/          # SPL token with extensions
│   ├── reward-engine/       # Core distribution logic
│   ├── oracle-validator/    # Verification mechanism
│   └── governance/          # DAO controls
├── tests/                   # Integration tests
├── scripts/                 # Deployment scripts
└── docs/                    # Technical documentation
```

## Development Setup
```bash
# Coming soon - testnet deployment Q2 2026
# Dependencies: Rust, Solana CLI, Anchor Framework

# Install dependencies
cargo build

# Run tests
anchor test

# Deploy to devnet
anchor deploy --provider.cluster devnet
```

## Testnet Deployment

**Devnet Address**: TBD (Q2 2026)  
**Testnet Address**: TBD (Q3 2026)  
**Mainnet Address**: TBD (Q1 2027)

## Security Audits

- **Phase 1**: Internal security review (Q2 2026)
- **Phase 2**: External audit by leading firm (Q3 2026)
- **Phase 3**: Public bug bounty (Q4 2026)

Target auditors: Trail of Bits, Zellic, Kudelski Security

## Contributing

Currently in stealth development phase. Public contributions will be accepted starting Q3 2026 after testnet launch.

## Documentation

See [neba-docs](https://github.com/NEBA-Protocol/neba-docs) for comprehensive technical documentation.

## License

MIT License - See LICENSE file for details

---

Built with Solana | Powered by AI | Secured by Mathematics
