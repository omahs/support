# Request escrow

## Escrowing Outstanding Payments On Invoices

## Who is it for?

Escrow is a contractual arrangement where a third party temporarily holds money or property, and disburses it only when a particular condition has been met.

Traditionally, escrow agents would perform this function. Today, smart contracts and programmable assets on blockchain ledgers can perform this function according to pre-set rules. Smart contract escrow services are cheaper and faster.

This is ideal for situations where payment is made - only after a service has been rendered, or a good has been delivered as agreed upon.

Escrow facilitates trust: from hiring a freelancer, to contracting the services of an agency, or even ordering stuff online.

A seller can see that the buyer has sufficient money on hand. At the same time, the buyer is assured that the seller will not disappear with the funds without delivering the goods or services as promised.

## How does it work?

### Consider two parties:

**Client** (paying for a good or service) and **Contractor** (expecting to be paid)

### Escrow process

The escrow process works in the following way.

**1. Agreement**: The client and contractor enter into a contractual agreement.

**2. Invoicing & Escrow**:
The contractor creates and sends an invoice to the client, asking them to deposit the funds due on the invoice into the escrow smart contract.

**3. Delivery/Fulfillment**: The contractor commences work, and notifies the client when the job is done.

**4. Payment**: If the client is satisfied with the job, they release the funds to the contractor.

## Dispute Resolution

Disputes may arise between the parties. If the client is not satisfied with the job performed by the contractor, or if the contractor believes the client is refusing to pay for a job done, either party may freeze the escrow.

Freezing the escrow means that the funds will remain irreversibly locked in the smart contract for 12 months, before being released back to the client’s wallet address. The contractor will not be paid, but the client will also be penalized on the time value of the frozen funds.

Our current approach to dispute resolution is a simple, and cost-effective one. By imposing costs on all parties in the event of a dispute, we aim to incentivize both parties to: (i) reach an amicable settlement, and (ii) only engage with trustworthy counterparts in the first place.

Admittedly, this approach can reduce, but not eliminate the potential for abuse. In the future, we may offer arbitral options for dispute resolution. But those are likely to incur additional costs on both disputing parties.

Note: the smart contract is still in beta, and hasn't been audited. In light of this, Request is committed to providing payouts in the event of a failure of the smart contract to perform as anticipated, up to a maximum sum of $5,000.

### Unresponsive Client

Clients may become unresponsive for various reasons, other than bad faith. For instance, it is possible that the client loses their private keys and they simply cannot release the money to the contractor.

In that case, the contractor can initiate an emergency claim on the smart contract. When this happens, after 6 months, the contractor will receive the money without the need for the client’s approval.

However, the client can reverse the emergency claim at any time before the 6 month period is up. This is to prevent contractors from abusing the feature by initiating frivolous emergency claims, with the intent of claiming the payout without delivering.

Should a client acting in bad faith attempt to avoid payment by becoming unresponsive, while reversing emergency claims raised, the contractor can simply walk away, leaving the funds held in escrow. The client acting in bad faith can only retrieve the funds from the smart contract after 12 months by freezing the escrow.

### Unresponsive Contractor

If the client is not satisfied with the job performed by the contractor, they have the option to freeze the escrow.

Freezing the escrow means that the money will remain in the contract for 12 months and after that, the client will be able to withdraw the full amount.

We have put the duration of 12 months to incentivize clients to try their very best to reach an agreement with their contractor before using this feature, however, they must have the option to retrieve their money as a last resort.

**_Warning: this action is irreversible._** Once an escrow has been frozen, it cannot be unfrozen, not even by the client, the money will remain locked for 12 months.

In that case, the client can freeze the escrow in the smart contract and they can get their money after a 12-month freezing period.
