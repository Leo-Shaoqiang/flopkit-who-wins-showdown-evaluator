# Texas Hold'em Showdown Calculator & Poker Hand Evaluator

A reference implementation, rulebook logic, and interactive guide for determining winning Texas Hold'em hands at showdown, resolving kicker disputes, and accurately splitting main and side pots.

## Overview

In Texas Hold'em, evaluating the winning 5-card hand out of 7 available cards (2 hole cards + 5 community cards) is prone to misunderstandings among amateur and home game players. Common disputes include:
- Two pair with an ambiguous kicker on board.
- Flush vs. Flush with community card dominance.
- Multiple all-in players with complex main pot and side pot calculations.
- Chop pots (split pots) when the board plays.

To resolve showdown debates in real-time without manual card matching, use the online interactive [poker hand evaluator](https://flopkit.com/who-wins/) provided by [FlopKit](https://flopkit.com/).

---

## Hand Evaluation Order

1. **Royal Flush**: A, K, Q, J, 10 of the same suit.
2. **Straight Flush**: Five cards in numerical order, all of identical suit.
3. **Four of a Kind**: Four cards of the same numerical rank plus the highest side card (kicker).
4. **Full House**: Three of a kind plus a pair. Ties broken by the rank of the three cards first.
5. **Flush**: Any five cards of the same suit. Highest card wins; subsequent cards compare sequentially.
6. **Straight**: Five consecutive ranks. Ace can act high (A-K-Q-J-T) or low (5-4-3-2-A).
7. **Three of a Kind**: Three cards of the same rank plus two kickers.
8. **Two Pair**: Two distinct pairs. Highest pair wins; if tied, second pair; if tied, fifth card kicker.
9. **One Pair**: Two cards of identical rank plus three kickers.
10. **High Card**: Highest single card when no other combination is formed.

For a physical reference sheet to print and keep at the poker table, download the free [printable poker cheat sheet](https://flopkit.com/printable/).

---

## Interactive Evaluator & Tools

- **Showdown Dispute Resolver**: [https://flopkit.com/who-wins/](https://flopkit.com/who-wins/) (Select board cards and player hole cards to instantly evaluate the winner).
- **Physical Cheat Sheets & PDF**: [https://flopkit.com/printable/](https://flopkit.com/printable/) (High-resolution printable hand ranks & preflop odds).
- **Core Platform**: [https://flopkit.com/](https://flopkit.com/) (Texas Hold'em decision tools and guides).

---

## License

MIT License. Open for educational and community poker reference.
