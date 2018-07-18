# Ethereum Casino

An implementation of a simple casino on the Ethereum blockchain

- Mintable and burnable ERC223 token used as "casino chips" (CHP)
- Send ETH to the casino (must be a multiple of the chipPrice) and the casino will send CHP back to you
- Send CHP to the casino and the casino will send you ETH
- Tables are separate contracts on the chain and are managed by the casino
- Bet at a table by sending CHP tokens and your betting number as data to the table
- The table uses the commit/reveal approach for randomization when the dealer closes the round (rien ne va plus)
- If you win, you get back twice your betted CHP (winning chance is 1/3)
