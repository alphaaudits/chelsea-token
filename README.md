## ChelseaDAO Reference Implementation

Contracts deployed at the following addresses:

- **ChelseaDAOERC20:** [0x94b657509b2fd076ad3e4b6035167879ded67cbb](https://etherscan.io/address/0x94b657509b2fd076ad3e4b6035167879ded67cbb)
  An ERC20 token used to raise funds, handle refunds in the event of project failure, and calculate voting weights. Minting is public at a rate of 1:1 with ether.

- **ChelseaDAO:** [0x014af5aedcdaa8fa1453e619c6e6c54671273ee0](https://etherscan.io/address/0x014af5aedcdaa8fa1453e619c6e6c54671273ee0)
  A governor that hosts the system’s ability to create proposals.

- **ChelseaDAOTimelockController:** [0x55bd9616b5b8233f92358b35cb2170efeedaa1df](https://etherscan.io/address/0x55bd9616b5b8233f92358b35cb2170efeedaa1df)
  A timelock controller that acts as the ultimate executor of proposals, adding a safety delay in case of a potentially dangerous operation.
