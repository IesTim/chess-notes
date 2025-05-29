# Caro-Kann Defence
This module is an in depth overview of everything I know and learned so far about the Caro-Kann Defence. The ECO classification of the Caro-Kann Defence is B10-B19. In this module I will try to learn as much as possible about each variation.

## Contents
- [General Structure](#general-structure)
- [Variations](#variations)
    - [Exchange variation: B11-B12](#exchange-variation)
        - [Opening plan](#exchange-variation---opening-plan)
        - [Middle game plan](#exchange-variation---middle-game-plan)
    - [Advance Variation: B13-B14](#advance-variation)
    - [Classical Variation: B15-B16](#classical-variation)
    - [Panov-Botvinnik Attack: B17](#panov-botvinnik-attack)
    - [Two Knights Variation: B18](#two-knights-variation)
    - [Fantasy Variation: B19](#fantasy-variation)



## General structure
The Caro-Kann Defence is a solid set-up based opening for black. The two opening moves are the following. The ECO classification of the main Caro-Kann Defence is B10, and looks the following:
```chess
orientation: black
fen: rnbqkbnr/pp2pppp/2p5/3p4/3PP3/8/PPP2PPP/RNBQKBNR w KQkq - 0 3
```

## Variations
### Exchange Variation
In the exchange variation white captures the pawn on d5:
```pgn
orientation: black
1. e4 c6 2. d4 d5 3. exd5 cxd5
```

#### Exchange Variation - Opening plan

The general idea of the exchange variation is to focus on the queen's side (a,b,c file). Here we can make use of the a and b pawn to lead a minority attack in the middle game. We can use the half open c-file with the rook to further help the attack.
We follow-up with basic development putting the pieces on logical squares and casteling king's side. Note that we only play e6 whenever our white bishop is developed.

```chess
orientation: black
fen: rnbqkbnr/pp2pppp/8/3p4/3P4/8/PPP2PPP/RNBQKBNR w KQkq - 0 4
arrows: b8->c6 g8->f6 c8->g4 e7->e6 f8->e7 a8->c8 
squares: g4 
```

There are some general principles we should adhere to in the opening:
-  Whenever white plays h3, attacking the bishop we trade whenever Kc3 or Bb5 has been played. Otherwise we play Bh5. 
 
```chess
orientation: black
fen: r2qkbnr/pp2pppp/2n5/3p4/3P2b1/2N2N1P/PPP2PP1/R1BQKB1R b KQkq - 0 6
lastMove: h2 h3
arrows: f1->b5 g4->f3
squares: c3 b5
```



- Whenever white plays Bf4 we can offer a trade of the dark square bishops by playing Bd6.

```chess
orientation: black
fen: r2qk2r/pp3ppp/2nbpn2/3p4/3P1B2/2N2B1P/PPP2PP1/R2QK2R w KQkq - 2 10
lastMove: f8 d6
arrows: f8->d6
squares: d6
```
#### Exchange Variation - Middle game plan

After we succesfully developped the pieces in the opening, the goal is now to damage the white pawn structure by using the open c file. We can prepare by stacking rooks and queen on the c file, move away the knight and attack with the pawns. Whenever white tries to play c3, we can play b5 b4 to undermine the structure of white and create an advantage. 

### Advance Variation
In the advance variation white pushes the e pawn, note that every variation where the white e pawn ends up on e5 is considered the advance variation:
```pgn
orientation: black
1. e4 c6 2. d4 d5 3. e5
```
#### Advance Variation - Opening plan
The main idea is to put a lot of pressure on the d4 square. We can do this by playing normal development moves. Take note of the order we play them in. 

```chess
orientation: black
```

### Classical Variation
### Panov-Botvinnik Attack
### Two Knights Variation
### Fantasy Variation