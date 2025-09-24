🧪 3.Rebasing cada 3 meses (+10%)
`solidity
uint256 public rebaseRate = 110; // +10%
uint256 public rebaseInterval = 90 days;
`


🧪 2.Solo cambia el rebaseRate y rebaseInterval: Rebasing cada 6 meses (+20%)

`solidity
uint256 public rebaseRate = 120; // +20%
uint256 public rebaseInterval = 180 days;
`

Todo lo demás del contrato puede permanecer igual.

---

🧪 3. Rebasing cada 12 meses (+30%)

`solidity
uint256 public rebaseRate = 130; // +30%
uint256 public rebaseInterval = 365 days;
`
