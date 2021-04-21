# NeumBorn
Função para calcular Equação Integral de Fredholm de 2° espécie.
A função NeumBorn é baseada na técnica SOLUÇÃO PELO OPERADOR INTEGRAL LINEAR: SÉRIE DE NEUMANN (1877) - BORN (1926) para as Equações Integrais de FredHolm.

A função NeumBorn solicitará 4 parâmetros de entrada:
Primeiro Parâmetro K(x,t):
	Função Kernel na qual depende das variáveis x e t

Segundo Parâmetro F(x):
	Função de onda incidente F(x) na qual depende da variável x

Terceiro Parâmetro:
	O limite superior da integral

Quarto Parâmetro:
	O limite inferior da integral

Quinto Parâmetro:
	Até que ordem será calculada

Sexto Parâmetro:
	se deseja imprimir os coeficientes de cada ordem de Lambda

Sétimo Parâmetro:
	Se deseja que a função tente calcular 
	a solução completa da série, lembrando
	que nem sempre é possível

A função NeumBorn retornará uma equação dependente de x e de Lambda";
