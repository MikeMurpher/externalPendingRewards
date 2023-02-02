# externalPendingRewards

Smart Contract For Fetching User Rewards From All Pools on a Masterchef V1 contract in a single call

Pass the UserAddress and MasterChef Address into either the Masterchef or ReflectorChef function to return the total rewards as a uint256.

In your application you can use parseInt() on the return value to convert to an Integer Number

This figure can then be divided by the decimals using 10**{yourRewardTokenDecimal}


