!função objetivo para preços de rações;
[receita] max = 100*x + 75*y;
!Restrições;
[Cereral] 3*x + 4*y       <= 2000;      
[Proteina] 2*x + 1*y      <= 1000;
Receitax= 100*x;
Receitay= 75*y;
[DemandaY] y >= 250; !atender a segunda demanda por ser mais barata
!@gin(x); !@gin(y);
