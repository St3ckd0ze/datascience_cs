Dataset: https://www.kaggle.com/datasets/mateusdmachado/csgo-professional-matches

## Clean Dataset
we need:
- Team Economies (Ausrüstungswert)
- Startseite (CT/T)
- Map
- Round Number
- Round Winner

what we have:
| date | match_id | event_id | team_1 | team_2 | best_of | _map | t1_start | t2_start | 1_t1 | 2_t1 | 3_t1 | 4_t1 | 5_t1 | 6_t1 | 7_t1 | 8_t1 | 9_t1 | 10_t1 | 11_t1 | 12_t1 | 13_t1 | 14_t1 | 15_t1 | 16_t1 | 17_t1 | 18_t1 | 19_t1 | 20_t1 | 21_t1 | 22_t1 | 23_t1 | 24_t1 | 25_t1 | 26_t1 | 27_t1 | 28_t1 | 29_t1 | 30_t1 | 1_t2 | 2_t2 | 3_t2 | 4_t2 | 5_t2 | 6_t2 | 7_t2 | 8_t2 | 9_t2 | 10_t2 | 11_t2 | 12_t2 | 13_t2 | 14_t2 | 15_t2 | 16_t2 | 17_t2 | 18_t2 | 19_t2 | 20_t2 | 21_t2 | 22_t2 | 23_t2 | 24_t2 | 25_t2 | 26_t2 | 27_t2 | 28_t2 | 29_t2 | 30_t2 | 1_winner | 2_winner | 3_winner | 4_winner | 5_winner | 6_winner | 7_winner | 8_winner | 9_winner | 10_winner | 11_winner | 12_winner | 13_winner | 14_winner | 15_winner | 16_winner | 17_winner | 18_winner | 19_winner | 20_winner | 21_winner | 22_winner | 23_winner | 24_winner | 25_winner | 26_winner | 27_winner | 28_winner | 29_winner | 30_winner |

what we need:
| match_id | map | round | team1_equip | team2_equip | team1_side | team2_side | winner |

