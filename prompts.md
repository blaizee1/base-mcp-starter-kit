# Base MCP Prompt Templates; DeFi Yield Optimizer

Copy and paste these directly into Claude/Cursor/ChatGPT **after** adding the Base MCP skill (`base-mcp`).

### 1. Full Autonomous Yield Optimizer (Most Used)
Act as my autonomous DeFi yield optimizer on Base.
1. Check my current wallet balances (USDC, ETH, etc.).
2. Scan Morpho and Moonwell for the highest APY vaults.
3. Compare Aerodrome vs Uniswap liquidity incentives for the same pairs.
4. Suggest the single best move (swap + deposit) and prepare the exact transaction.
Only proceed after I say "approve".

### 2. Daily Rebalance
Run my daily yield rebalance on Base:
1. Withdraw anything earning less than 8% APY
2. Swap to the current highest yielding asset on Morpho or Moonwell
3. Deposit and show me the new APY + expected daily earnings

### 3. Quick 100 USDC Deployment
I have 100 USDC. Find the absolute best place to put it right now for maximum yield on Base (Morpho or Moonwell only). Prepare the exact transaction steps.

### 4. Liquidity Provision Comparison
Compare providing liquidity on Aerodrome vs Uniswap for ETH/USDC pair right now.
Show:
 -Current APR
 -Fees earned
 -Incentives
  Recommend the better option and prepare the full LP position transaction.

### 5. Conservative / Risk Aware Mode
Conservative mode: Only use blue chip Morpho vaults or Moonwell. No leverage. Show me the top 3 safest yield options right now and prepare the safest deposit.

### 6. Emergency Withdraw + Redeploy
Check all my current positions. Withdraw anything with APY below 6%. Redeploy everything into the single highest yielding safe vault on Morpho/Moonwell.

### 7. Portfolio Overview
Give me a full portfolio overview of my Base wallet and all active DeFi positions. Show total value, current yield, and one-sentence recommendation.

**Pro tip:** After the AI responds with a transaction, just say “execute” or “approve” and Base MCP will handle it with your approval in the Base App.
