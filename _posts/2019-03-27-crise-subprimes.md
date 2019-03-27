# D'où vient la crise de 2007

Hier soir, j'ai une fois de plus regardé *The Big Short*, le film retraçant l'histoire de ceux ayant parié que le marché immobilier allait s'éfondrer en 2007, à raison. Finallement, j'ai enfin réussi à comprendre comment la crise économique est survenu, enfin. Repassons tout ça en revue et intéressons nous à la finance.

##Une histoire de prêts immobiliers

Bon, reprenons tout depuis le début. Vous avez des banques, qui proposent des prêts hypothécaire : on vous file de l'argent pour acheter votre maison, or si vous payez pas, la banque vous reprend votre maison. Pour la banque, tout est bénéfique car si le prêté paye, la banque récupère les intérêts, si le prêté ne paye pas, la banque saisit sa maison et la revend avec une plus-value.

Pour que ce modèle fonctionne, il est nécessaire de prêter à une extrême majorité de gens qui ont assez d'argent pour rembourser les prêts. En effet, si on a une part importante des prêtés qui ne le peuvent pas, alors beaucoup de maisons seront saisies  par la banque pour être remise en vente, mais l'offre de maison sera au-dessus de la demande (tmtc Adam Smith).

Malheureusement, c'est ce qu'il s'est passé en 2007. Les sociétés de prêt pariait à tort que le risque final que la délivrance du prêt endette à la fin était faible. Finalement, beaucoup de prêtés n'ont pas remboursé leur maison, gonflant l'offre des maisons alors saisies, provoquant un endettement puis une faillite de ces mêmes sociétés.

Cela aurait pu s'arrêter là : les sociétés de prêt défaillantes chûtent et celles qui sont restées raisonnables dans la délivrance des prêts subsistent. Seul le secteur du prêt immobilier américain aurait été touché, le sauvetage aurait été assez simple. MAIS NON!

##De la titrisation à l'endettement de tout un marché

Quand les banques ont délivré leur prêt immobilier, elles n'ont pas gardé leur créance dans leur bilan en attendant que ces prêts soient remboursés. Non, elles ont *vendu* ces prêts à d'autres socétés. Sauf que qui accepterait d'échanger la créance d'un prêt d'une seule personne ? Il suffit que le mec a qui on a prêté meurt pour que hop, la créance ne soit pas renflouée.

Pour éviter ça, les banques ont créé des MBS (Mortgage-Backed Security) : la banque crée un paquet de prêts, trie ces prêts en différentes tranches au risque plus ou moins grand, puis vendent chaque tranche à des investisseurs. Non seulement le risque sort de la banque (= société de prêt), mais en plus l'investisseur ne support qu'une infime partie du risque.

On s'est donc retrouvé avec des investisseurs ayant supporté le risque de tranches à *bas risque* (noté AAA), et d'autres ayant supporté le risque de tranches à *haut risque* (B) : voilà ce qu'est une *subprime*, une obligation (la vente d'une créance) hyper risquée, mais rapportant énormément (car plus le risque du prêt est elevé, plus la marge de sécurité est forte également).

Ensuite, ces mêmes investisseurs, souhaitant se débarasser des risques de leurs investissements, ont eux aussi créé un paquet de tranches de MBS produisant des CDO (Collateralized Debt Obligations). Les CDO sont des paquet de tranches pourries (*subprimes*) de MBS, vendu à d'autres investisseurs. Le tour de magie est qu'en créant ce paquet, on re-trie en tranches plus ou moins risquées (de AAA à B) le CDO. Finalement, quand un investisseur achète une tranche AAA de CDO, il ne se rend pas compte qu'il achète un paquet de *subprimes*, soit des tranches B de MBS.

Mais ce n'est pas terminé ! Par la suite, beaucoup d'agents financiers ont contracté des CDS (Credit default swap) : un pari sur l'évolution (ascendante ou descendante) de la valeur d'un titre. Ici, beaucoup d'agents ont contracté des CDS sur le pari que la valeur des CDO ne cesserait d'augmenter (*pourquoi le marché de l'immobilier baisserait-il enfin ? C'est le marché le plus stable du pays*). Petit à petit, les agents ont contracté des CDS de CDS, puis des CDS de CDS de CDS, etc.

##Et hop, ça fait des chocapics

Or, à la fin, beaucoup de personnes n'ont pas remboursé le prêt de leur maison.

Vous comprendrez que cela a bouleversé le marché, provoquant la chute des prêts, donc des MBS, donc des CDO, donc des CDS. Or, comme tout ça était atomisé PARTOUT sur le marché mondial de la finance, tout est tombé en rade. Pas que les sociétés de prêt.