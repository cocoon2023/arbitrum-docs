

### Active Validator {#active-validator}
<p>A staked <a href="/intro/glossary#validator">Validator</a>  that makes disputable assertions to advance the state of an Arbitrum chain or to challenge the validity of others' assertions. (Not to be confused with the <a href="/intro/glossary#sequencer">Sequencer</a> ).</p>

### Address Alias {#address-alias}
<p>An address deterministically generated from an L1 contract address used on L2 to safely identify the source of an L1 to L2 message.</p>

### Arb Token Bridge {#arb-token-bridge}
<p>A series of contracts on an Arbitrum chain and its underlying chain that facilitate trustless movement of ERC-20 tokens between the two layers.</p>

### Arbitrum {#arbitrum}
<p>A suite of Ethereum layer-2 scaling technologies built with the <a href="/intro/glossary#arbitrum-nitro">Arbitrum Nitro</a> tech stack that includes <a href="/intro/glossary#arbitrum-one">Arbitrum One</a> (a live implementation of the <a href="/intro/glossary#arbitrum-rollup-protocol">Arbitrum Rollup Protocol</a>) and <a href="/intro/glossary#arbitrum-nova">Arbitrum Nova</a> (a live implementation of the <a href="/intro/glossary#arbitrum-anytrust-protocol">Arbitrum AnyTrust Protocol</a>).</p>

### Arbitrum AnyTrust Chain {#arbitrum-anytrust-chain}
<p>An <a href="/intro/glossary#arbitrum-chain">Arbitrum chain</a> that implements the <a href="/intro/glossary#arbitrum-anytrust-protocol">Arbitrum AnyTrust Protocol</a>.</p>

### Arbitrum AnyTrust Protocol {#arbitrum-anytrust-protocol}
<p>An Arbitrum protocol that manages data availability with a permissioned set of parties known as the <a href="/intro/glossary#data-availability-committee-dac">Data Availability Committee (DAC)</a>. This protocol reduces transaction fees by introducing an additional trust assumption for data availability in lieu of Ethereum's <a href="/intro/glossary#trustless">Trustless</a> data availability mechanism. <a href="/intro/glossary#arbitrum-nova">Arbitrum Nova</a> is an example of an AnyTrust chain; <a href="/intro/glossary#arbitrum-one">Arbitrum One</a> is an alternative chain that implements the purely trustless (and more L1-gas intensive) <a href="/intro/glossary#arbitrum-rollup-protocol">Arbitrum Rollup Protocol</a>.</p>

### Arbitrum chain {#arbitrum-chain}
<p>A blockchain that runs on the Arbitrum protocol. Arbitrum chains are EVM compatible, and use an underlying EVM chain (e.g., Ethereum) for settlement and for succinct fraud-proofs (as needed).  Arbitrum chains come in two forms: <a href="/intro/glossary#arbitrum-rollup-chain">Arbitrum Rollup Chain</a>s and <a href="/intro/glossary#arbitrum-anytrust-chain">Arbitrum AnyTrust Chain</a>s. </p>

### Arbitrum Classic {#arbitrum-classic}
<p><a href="https://github.com/OffchainLabs/arbitrum">Old Arbitrum stack</a> that used custom virtual machine ("AVM"); no public Arbitrum chain uses the classic stack as of 8/31/2022 (they instead use <a href="/intro/glossary#arbitrum-nitro">Arbitrum Nitro</a> ).</p>

### Arbitrum Full Node {#arbitrum-full-node}
<p>A party who keeps track of the state of an Arbitrum chain and receives remote procedure calls (RPCs) from clients. Analogous to a non-staking L1 Ethereum node.</p>

### Arbitrum Nitro {#arbitrum-nitro}
<p>Current Arbitrum tech stack; runs a fork of <a href="/intro/glossary#geth">Geth</a> and uses WebAssembly as its underlying VM for fraud proofs.</p>

### Arbitrum Nova {#arbitrum-nova}
<p>The first <a href="/intro/glossary#arbitrum-anytrust-chain">Arbitrum AnyTrust Chain</a> running on Ethereum mainnet. Introduces cheaper transactions; great for gaming and social use-cases. Implements the <a href="/intro/glossary#arbitrum-anytrust-protocol">Arbitrum AnyTrust Protocol</a>, not the <a href="/intro/glossary#arbitrum-rollup-protocol">Arbitrum Rollup Protocol</a> protocol.</p>

### Arbitrum One {#arbitrum-one}
<p>The first <a href="/intro/glossary#arbitrum-rollup-chain">Arbitrum Rollup Chain</a> running on Ethereum mainnet. Fully trustless; inherits Ethereum's base-layer security guarantees without introducing additional trust assumptions; great for decentralized finance and other use-cases that demand L1-level trustlessness.</p>

### Arbitrum Orbit {#arbitrum-orbit}
<p>Arbitrum Orbit refers to the ability for anyone to permissionlessly deploy <a href="/intro/glossary#layer-3-l3">Layer 3 (L3)</a> chains on top of Arbitrum <a href="/intro/glossary#layer-2-l2">Layer 2 (L2)</a> chains.</p>

### Arbitrum Rollup Chain {#arbitrum-rollup-chain}
<p>An <a href="/intro/glossary#arbitrum-chain">Arbitrum chain</a> that implements the <a href="/intro/glossary#arbitrum-rollup-protocol">Arbitrum Rollup Protocol</a>.</p>

### Arbitrum Rollup Protocol {#arbitrum-rollup-protocol}
<p>A trustless, permissionless Arbitrum protocol that uses its underlying base layer for data availability and inherits its security. This protocol is implemented by our <a href="/intro/glossary#arbitrum-one">Arbitrum One</a> chain. </p>

### ArbOS {#arbos}
<p>Arbitrum's "operating system" that trustlessly handles system-level operations; includes the ability to emulate the EVM.</p>

### Assertion {#assertion}
<p>A staked claim by an Arbitrum <a href="/intro/glossary#validator">Validator</a>. An assertion may, e.g., propose a new <a href="/intro/glossary#rblock">RBlock</a>, or may be a step in a <a href="/intro/glossary#challenge">Challenge</a>.</p>

### Batch {#batch}
<p>A group of Arbitrum transactions posted in a single transaction on the <a href="/intro/glossary#underlying-chain">Underlying Chain</a>  into the <a href="/intro/glossary#fast-inbox">Fast Inbox</a>  by the <a href="/intro/glossary#sequencer">Sequencer</a>.</p>

### Blockchain {#blockchain}
<p>A distributed digital ledger that is used to record transactions and store data in a secure, transparent, and tamper-resistant way, notably in cryptocurrency protocols. </p>

### BOLD {#bold}
<p>Short for "Bounded Liquidity Delay"; latest version of the Arbitrum <a href="/intro/glossary#challenge-protocol">Challenge protocol</a> designed to eliminate <a href="https://medium.com/offchainlabs/solutions-to-delay-attacks-on-rollups-434f9d05a07a">delay attack vectors</a> (see <a href="https://medium.com/offchainlabs/bold-permissionless-validation-for-arbitrum-chains-9934eb5328cc">here</a> for more). Not currently on mainnet. </p>

### 🧢 CAP Finance {#cap-finance}
<p>Widely considered the most degen community on Arbitrum.<br />
<br />
<a href="https://cap.io/">CAP</a> is a decentralized trading protocol. It's designed to be fast and easy to use by anyone.</p>

### Chain state {#chain-state}
<p>A particular point in the history of an <a href="/intro/glossary#arbitrum-chain">Arbitrum chain</a>. A chain's state is determined by applying Arbitrum state-transition function to sequence of transactions (i.e., the chain's history).</p>

### Challenge {#challenge}
<p>When two <a href="/intro/glossary#staker">Staker</a>s disagree about the correct verdict on an <a href="/intro/glossary#assertion">Assertion</a>, those stakers can be put in a challenge. The challenge is refereed by the contracts on the underlying chain. Eventually one staker wins the challenge. The protocol guarantees that an honest  party will always win a challenge; the loser forfeits their stake. </p>

### Challenge Period {#challenge-period}
<p>Window of time (1 week on Arbitrum One) over which an asserted <a href="/intro/glossary#rblock">RBlock</a>  can be challenged, and after which the RBlock can be confirmed.</p>

### Challenge protocol {#challenge-protocol}
<p>The protocol by which <a href="/intro/glossary#rblock">RBlock</a>s are submitted, disputed, and ultimately confirmed. The Challenge Protocol guarantees that only valid RBlocks will be confirmed provided that there is at least one honest <a href="/intro/glossary#active-validator">Active Validator</a>.</p>

### Child chain {#child-chain}
<p>An Arbitrum Chain that settles to an underlying <a href="/intro/glossary#parent-chain">Parent chain</a> . For example, Arbitrum One and Arbitrum Nova are child chains of Ethereum.</p>

### Client {#client}
<p>A program running on a user's machine, often in the user's browser, that interacts with contracts on an <a href="/intro/glossary#arbitrum-chain">Arbitrum chain</a>  and provides a user interface.</p>

### Confirmation {#confirmation}
<p>The decision by an <a href="/intro/glossary#arbitrum-chain">Arbitrum chain</a>  to finalize an <a href="/intro/glossary#rblock">RBlock</a>  as part of the chain's history. Once an RBlock is confirmed its <a href="/intro/glossary#l2-to-l1-message">L2 to L1 Message</a>s  (e.g., withdrawals) can be executed.</p>

### Cross-chain message {#crosschain-message}
<p>An action taken on some chain A which asynchronously initiates an additional action on chain B. </p>

### Custom Arb-Token {#custom-arbtoken}
<p>Any L2 token contract registered to the <a href="/intro/glossary#arb-token-bridge">Arb Token Bridge</a> that isn't a standard arb-token (i.e., a token that uses any gateway other than the <a href="/intro/glossary#standarderc20-gateway">StandardERC20 gateway</a> ).</p>

### Custom gateway {#custom-gateway}
<p>Any <a href="/intro/glossary#token-gateway">Token Gateway</a> that isn't the <a href="/intro/glossary#standarderc20-gateway">StandardERC20 gateway</a>.</p>

### dApp {#dapp}
<p>Short for "decentralized application." A dApp typically consists of smart contracts as well as a user-interface for interacting with them.</p>

### Data Availability Certificate {#data-availability-certificate}
<p>Signed promise from a <a href="/intro/glossary#data-availability-committee-dac">Data Availability Committee (DAC)</a> attesting to the availability of a batch of data for an <a href="/intro/glossary#arbitrum-anytrust-chain">Arbitrum AnyTrust Chain</a>.</p>

### Data Availability Committee (DAC) {#data-availability-committee-dac}
<p>A permissioned set of parties responsible for enforcing data availability in an <a href="/intro/glossary#arbitrum-anytrust-protocol">Arbitrum AnyTrust Protocol</a> chain. See <em><a href="https://medium.com/offchainlabs/introducing-anytrust-chains-cheaper-faster-l2-chains-with-minimal-trust-assumptions-31def59eb8d7">Introducing AnyTrust Chains: Cheaper, Faster L2 Chains with Minimal Trust Assumptions</a></em> to learn more.</p>



### Defensive Validator {#defensive-validator}
<p>A <a href="/intro/glossary#validator">Validator</a> that watches an Arbitrum chain and takes action (i.e., stakes and challenges) only when and if an invalid <a href="/intro/glossary#assertion">Assertion</a> occurs.</p>

### Delayed Inbox {#delayed-inbox}
<p>A contract that holds <a href="/intro/glossary#parent-chain">Parent chain</a> initiated messages to be eventually included in the <a href="/intro/glossary#fast-inbox">Fast Inbox</a>. Inclusion of messages doesn't depend on the <a href="/intro/glossary#sequencer">Sequencer</a>.</p>

### Dissection {#dissection}
<p>A step in the <a href="/intro/glossary#challenge-protocol">Challenge protocol</a>  in which two challenging parties interactively narrow down their disagreement until they reach a <a href="/intro/glossary#one-step-proof">One Step Proof</a>.</p>

### 💎 Dopex {#dopex}
<p>A shiny gem in the Arbitrum community.<br />
<br />
Commonly associated with the esteemed Diamond Pepe's NFT and Dopex community. Dopex is a decentralized options exchange protocol on Arbitrum.</p>

### Ethereum Wallet {#ethereum-wallet}
<p>A software application used for transacting with the Ethereum <a href="/intro/glossary#blockchain">Blockchain</a>.</p>

### Fair Ordering Algorithm {#fair-ordering-algorithm}
<p>BFT algorithm in which a committee comes to consensus on transaction ordering; current single-party <a href="/intro/glossary#sequencer">Sequencer</a> on Arbitrum may eventually be replaced by a fair-ordering committee.</p>

### Fast Exit / Liquidity Exit {#fast-exit--liquidity-exit}
<p>A means by which a user can bypass an Arbitrum chain's <a href="/intro/glossary#challenge-period">Challenge Period</a> when withdrawing fungible assets (or more generally, executing some "fungible" L2 to L1 operation); for trustless fast exits, a liquidity provider facilitates an atomic swap of the asset on L2 directly to L1.</p>

### Fast Inbox {#fast-inbox}
<p>Contract that holds a sequence of messages sent by clients to an Arbitrum Chain; a message can be put into the fast Inbox directly by the <a href="/intro/glossary#sequencer">Sequencer</a>  or indirectly through the <a href="/intro/glossary#delayed-inbox">Delayed Inbox</a>.</p>

### Force-Inclusion {#forceinclusion}
<p>Censorship resistant path for including a message into an Arbitrum chain via the <a href="/intro/glossary#delayed-inbox">Delayed Inbox</a> on its <a href="/intro/glossary#parent-chain">Parent chain</a>; bypasses any Sequencer involvement.</p>

### Fraud proof {#fraud-proof}
<p>The means by which an <a href="/intro/glossary#active-validator">Active Validator</a> proves to its underlying chain that an invalid state transition has taken place.</p>

### Gas Price Floor {#gas-price-floor}
<p>Protocol-enforced minimum gas price on an Arbitrum chain; currently 0.1 gwei on <a href="/intro/glossary#arbitrum-one">Arbitrum One</a> and 0.01 gwei on <a href="/intro/glossary#arbitrum-nova">Arbitrum Nova</a>.</p>

### Gateway Router {#gateway-router}
<p>Contracts in the <a href="/intro/glossary#arb-token-bridge">Arb Token Bridge</a>  responsible for mapping tokens to their appropriate <a href="/intro/glossary#token-gateway">Token Gateway</a>.</p>

### Generic-Custom Gateway {#genericcustom-gateway}
<p>A particular <a href="/intro/glossary#custom-gateway">Custom gateway</a> via which an L1 token contract can be registered to a token contract deployed to L2. A useful alternative to the <a href="/intro/glossary#standarderc20-gateway">StandardERC20 gateway</a> for projects that wish to control the address of their L2 token contract, maintain L2 token contract upgradability, and for various other use-cases. </p>

### Geth {#geth}
<p>An execution-layer client that defines the Ethereum state transition function and handles network-layer logic like transaction memory pooling. <a href="/intro/glossary#arbitrum-nitro">Arbitrum Nitro</a> utilizes a fork of Geth to implement Arbitrum's state transition function.</p>

### 🫐 GMX {#gmx}
<p>If you've seen some blueberries wandering around on crypto Twitter, you might wonder .. where did they come from?<br />
<br />
The iconic blueberries come from the community of the decentralized exchange, GMX.</p>

### L2 Block {#l2-block}
<p>Data structure that represents a group of L2 transactions (analogous to L1 blocks).</p>

### L2 to L1 Message {#l2-to-l1-message}
<p>A message initiated from within an Arbitrum chain to be eventually executed on <a href="/intro/glossary#layer-1-l1">Layer 1 (L1)</a> (e.g., token or Ether withdrawals). On Rollup chains like <a href="/intro/glossary#arbitrum-one">Arbitrum One</a>, the <a href="/intro/glossary#challenge-period">Challenge Period</a> must pass before an L2 to L1 message is executed.</p>

### Layer 1 (L1) {#layer-1-l1}
<p>The base protocol and underlying blockchain of the Ethereum network. Responsible for maintaining the integrity of the distributed ledger and executing smart contracts. Contains both Ethereum's execution layer and consensus layer.</p>

### Layer 2 (L2) {#layer-2-l2}
<p>Trustless scaling solutions built on top of Ethereum's <a href="/intro/glossary#layer-1-l1">Layer 1 (L1)</a> base protocol, such as state channels,  plasma chains, optimistic rollups, and ZK-rollups. Layer 2 solutions aim to increase scalability and reduce the cost of transactions on Ethereum's Layer 1 without introducing additional trust assumptions.</p>

### Layer 3 (L3) {#layer-3-l3}
<p>An Arbitrum chain whose core contract reside on an  Arbitrum <a href="/intro/glossary#layer-2-l2">Layer 2 (L2)</a> chain.</p>

### One Step Proof {#one-step-proof}
<p>Final step in a challenge; a single operation of the Arbitrum VM (<a href="/intro/glossary#wasm">WASM</a> ) is executed on the underlying chain, and the validity of its state transition is verified.</p>

### Outbox {#outbox}
<p>An L1 contract responsible for tracking <a href="/intro/glossary#l2-to-l1-message">L2 to L1 Message</a>s, including withdrawals, which can be executed once they are confirmed. The outbox stores a Merkle Root of all outgoing messages.</p>

### Parent chain {#parent-chain}
<p>EVM compatible chain that acts as the settlement layer for one or more Arbitrum Chains (aka <a href="/intro/glossary#child-chain">Child chain</a>  ). E.g., Ethereum is the parent chain of both Arbitrum One and Arbitrum Nova. Parent chain is synonymous with "underlying chain." </p>

### 🏴‍☠️ Pirate Nation {#pirate-nation}
<p>If you sail in the deep blue seas of Arbitrum, you may encounter some ships with pirate flags along the way ARRGG!<br />
<br />
The pirate flag originates from the Pirate Nation community. Pirate Nation is a game filled with high seas adventure, treasure, fun, and unexpected surprises.</p>

### RBlock {#rblock}
<p>An assertion by an Arbitrum <a href="/intro/glossary#validator">Validator</a> that represents a claim about an Arbitrum chain's state.</p>

### Retryable Autoredeem {#retryable-autoredeem}
<p>The "automatic" (i.e., requiring no additional user action) execution of a <a href="/intro/glossary#retryable-ticket">Retryable Ticket</a>  on an Arbitrum chain.</p>

### Retryable Redeem {#retryable-redeem}
<p>The execution of a <a href="/intro/glossary#retryable-ticket">Retryable Ticket</a> on L2; can be automatic (see <a href="/intro/glossary#retryable-autoredeem">Retryable Autoredeem</a>) or manual via a user-initiated L2 transaction.</p>

### Retryable Ticket {#retryable-ticket}
<p>An L1 to L2 cross chain message initiated by an L1 transaction sent to an Arbitrum chain for execution (e.g., a token deposit).</p>

### Reverse Token Gateway {#reverse-token-gateway}
<p>A <a href="/intro/glossary#token-gateway">Token Gateway</a> in which the <a href="/intro/glossary#child-chain">Child chain</a> gateway contract escrows and releases tokens, which the <a href="/intro/glossary#parent-chain">Parent chain</a> Gateway contract mints and burns tokens. This in the inverse to how "typical" gateways work.</p>

### Sequencer {#sequencer}
<p>An entity (currently a single-party on Arbitrum One) given rights to reorder transactions in the <a href="/intro/glossary#fast-inbox">Fast Inbox</a>  over a fixed window of time, who can thus give clients sub-blocktime <a href="/intro/glossary#soft-confirmation">Soft Confirmation</a>s. (Not to be confused with a <a href="/intro/glossary#validator">Validator</a>).</p>

### Sequencer Feed {#sequencer-feed}
<p>Off chain data feed published by the <a href="/intro/glossary#sequencer">Sequencer</a> which clients can subscribe to for <a href="/intro/glossary#soft-confirmation">Soft Confirmation</a>s of transactions before they are posted in <a href="/intro/glossary#batch">Batch</a>es.</p>

### Smart Contract {#smart-contract}
<p>A computer program whose operations are defined and executed within a blockchain consensus protocol.</p>

### 🐵 Smolverse {#smolverse}
<p>Near the core of Arbitrum community is Smolverse, a world filled with Smol Brains and Smol Bodies.<br />
<br />
If you see any Smol's with giga brains, swole arms or hear the sound of "EEEE" in the Arbitrum community, you've encountered the Smol Brains and Smol Bodies. </p>

### Soft Confirmation {#soft-confirmation}
<p>A semi-trusted promise from the <a href="/intro/glossary#sequencer">Sequencer</a>  to post a user's transaction in the near future; soft-confirmations happen prior to posting on the <a href="/intro/glossary#parent-chain">Parent chain</a>, and thus can be given near-instantaneously (i.e., faster than the parent chain's block times)</p>

### Speed Limit {#speed-limit}
<p>Target computation limit for an Arbitrum chain. <a href="/intro/glossary#arbitrum-one">Arbitrum One</a> and <a href="/intro/glossary#arbitrum-nova">Arbitrum Nova</a>  currently target 7,000,000 gas / second. When computation exceeds this limit, fees rise, ala <a href="https://notes.ethereum.org/@vbuterin/eip-1559-faq">EIP-1559</a>.</p>

### Staker {#staker}
<p>A <a href="/intro/glossary#validator">Validator</a> who deposits a stake (in Ether on <a href="/intro/glossary#arbitrum-one">Arbitrum One</a> and <a href="/intro/glossary#arbitrum-nova">Arbitrum Nova</a> ) to vouch for a particular <a href="/intro/glossary#rblock">RBlock</a>  in an Arbitrum Chain. A validator who stakes on a false RBlock can expect to lose their stake. An honest staker can recover their stake once the RBlock they are staked on has been confirmed.</p>

### Standard Arb-Token {#standard-arbtoken}
<p>An token contract on an Arbitrum chain deployed via the <a href="/intro/glossary#standarderc20-gateway">StandardERC20 gateway</a>; offers basic ERC20 functionality in addition to deposit / withdrawal affordances.</p>

### StandardERC20 gateway {#standarderc20-gateway}
<p><a href="/intro/glossary#token-gateway">Token Gateway</a> via which any underlying chain's ERC20 token can permissionlessly bridge; the StandardERC20 gateway contracts deploy a <a href="/intro/glossary#standard-arbtoken">Standard Arb-Token</a> on the <a href="/intro/glossary#child-chain">Child chain</a>   for each bridged token.</p>

### Stylus {#stylus}
<p>Upgrade to the <a href="/intro/glossary#arbitrum-nitro">Arbitrum Nitro</a> virtual machine that allows smart contract support for languages like Rust and C++ by taking advantage of Nitro's use of WASM. Currently on testnet (<a href="https://docs.arbitrum.io/stylus/stylus-gentle-introduction">read more</a>).</p>

### 🏹 Tales of Elleria {#tales-of-elleria}
<p>The bow and arrow are commonly associated with the Hero's of Tales of Elleria.<br />
<br />
Jump into the world of Elleria and go on adventures.</p>

### Time boost {#time-boost}
<p>A proposed (not currently live) transaction policy in which users can pay a fee to the <a href="/intro/glossary#sequencer">Sequencer</a> for a small ordering advantage. See [here](<a href="https://medium.com/offchainlabs/time-boost-a-new-transaction-ordering-policy-for-arbitrum-5b3066382d62">https://medium.com/offchainlabs/time-boost-a-new-transaction-ordering-policy-for-arbitrum-5b3066382d62</a>) for more.    </p>

### 🐸 Toadstoolz {#toadstoolz}
<p>Hidden in the Croakshire, you will find the friendly Toadstoolz. <br />
<br />
The iconic Toads of Arbitrum love to hunt BUGZ <br />
 and collect NFTs. !CROAK</p>

### Token Gateway {#token-gateway}
<p>A pair of contracts in the token bridge — one on the <a href="/intro/glossary#parent-chain">Parent chain</a>  , one on the <a href="/intro/glossary#child-chain">Child chain</a>  — that provide a particular mechanism for handling the transfer of tokens between layers. Token gateways currently active in the bridge include the <a href="/intro/glossary#standarderc20-gateway">StandardERC20 gateway</a> , the <a href="/intro/glossary#genericcustom-gateway">Generic-Custom Gateway</a> , and the <a href="/intro/glossary#weth-gateway">WETH Gateway</a>.</p>

### 🏡 TownStory  {#townstory-}
<p>If you see some homes along your road trip in the Arbitrum ecosystem, you've made it to TownStory.<br />
<br />
Build a warm and prosperous town with friends in TownStory.</p>

### Transaction {#transaction}
<p>A user-initiated interaction with a Blockchain. Transactions are typically signed by users via wallets and are paid for via transaction fees. </p>

### ✨ Treasure DAO {#treasure-dao}
<p>While exploring the Arbitrum ecosystem, you may see some shining stars.<br />
<br />
The iconic stars symbolize the magic of Treasure DAO. Treasure DAO is the decentralized gaming ecosystem connecting games and players on Arbitrum.</p>

### Trustless {#trustless}
<p>In the context of Ethereum, trustless refers to the ability of a system to operate without reliance on a central authority or intermediary. Instead, users place their trust in math and protocols.<br />
<br />
This is achieved through the use of cryptographic techniques and decentralized consensus mechanisms that let users verify the integrity of network transactions using open-source software. Trustless systems are considered to be more secure and resistant to fraud or tampering because they don't rely on a single point of failure that can be exploited by attackers.</p>

<p></p>



### Underlying Chain {#underlying-chain}
<p>Synonymous with <a href="/intro/glossary#parent-chain">Parent chain</a>.</p>

### Validator {#validator}
<p>An <a href="/intro/glossary#arbitrum-full-node">Arbitrum Full Node</a> that tracks the status of the chains' <a href="/intro/glossary#assertion">Assertion</a>s. A validator may be a <a href="/intro/glossary#watchtower-validator">Watchtower Validator</a>, a <a href="/intro/glossary#defensive-validator">Defensive Validator</a>, or an <a href="/intro/glossary#active-validator">Active Validator</a>. </p>

### WASM {#wasm}
<p>Widely supported binary code format for executable programs. Used by <a href="/intro/glossary#arbitrum-nitro">Arbitrum Nitro</a> for  <a href="/intro/glossary#fraud-proof">Fraud proof</a>s , and more broadly used by <a href="/intro/glossary#stylus">Stylus</a> to support performant smart contracts in a wide variety of languages.</p>

### Watchtower Validator {#watchtower-validator}
<p>A <a href="/intro/glossary#validator">Validator</a>  that never stakes / never takes on chain action, who raises the alarm (by whatever off-chain means it chooses) if it witnesses an invalid assertion.</p>

### WETH Gateway {#weth-gateway}
<p><a href="/intro/glossary#token-gateway">Token Gateway</a> for handing the bridging of wrapped Ether (WETH). WETH is unwrapped on L1 and rewrapped on L1 upon depositing (and vice-versa upon withdrawing), ensuring WETH on L2 always remains collateralized. </p>

### 👺 Zeeverse {#zeeverse}
<p>As you're exploring the Arbitrum world, you may bump into a world filled with monsters and Zee's.<br />
<br />
Explore a mythical Spirit Realm as a young Shaman and take part in strategic turn-based battles to help protect Zeeverse from the looming corrupted forces.</p>


