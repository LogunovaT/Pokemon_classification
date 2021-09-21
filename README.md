# Pokemon_classification
###### 1 Data source description ####
# The data was taken: https://gist.github.com/armgilles/194bcff35001e7eb53a2a8b441e8b2c6
# This dataset includes 721 Pokémon, including their number, name, first and second type, and basic stats: HP, attack, defense, special attack, special defense and speed.
# These are raw attributes that are used to calculate how much damage an attack will do in games.
# This dataset is about Pokemon games (NOT Pokemon cards or Pokemon Go)

###### 2 Description of data ####
#X .: ID for each Pokemon
#Name: The name of each Pokemon
#Type 1: every Pokemon has a type
#Type 2: Some Pokémon are dual type and have 2
#Total: the sum of all the stats that come after that, how strong the pokemon is
#HP: hit points or health points determine how much damage a Pokémon can take before fainting
#Attack: base modifier for normal attacks (e.g. Scratch, Hit)
#Defense: basic resistance against normal attacks
#SP Atk: special attack, base modifier for special attacks (e.g. fire burst, bubble ray)
#SP Def: Base Special Attack Damage Resistance
#Speed: Determines which Pokémon attacks first each round

###### 3 Problem statement ####
# Each Pokemon has a type that we can choose at the beginning
# Let's try to analyze which type is better and for what purpose

------------------------------------------------------------------

###### 1 Описание источника данных ####
# Данные взяты: https://gist.github.com/armgilles/194bcff35001e7eb53a2a8b441e8b2c6
# Этот набор данных включает 721 покемона, включая их количество, имя, первый и второй тип, а также основные характеристики: HP, атаку, защиту, особую атаку, особую защиту и скорость.
# Это необработанные атрибуты, которые используются для расчета, сколько урона атака нанесет в играх.
# Этот набор данных посвящен играм с покемонами (НЕ картам Pokemon или Pokemon Go)

###### 2 Описание данных ####
#X.: ID для каждого покемона
#Name: Имя каждого покемона.
# Тип 1: у каждого покемона есть тип
# Тип 2: некоторые покемоны являются двойными типами и имеют 2
#Total: сумма всех характеристик, которые появляются после этого, насколько силен покемон.
#HP: хиты или очки здоровья определяют, какой урон покемон может выдержать до обморока.
# Атака: базовый модификатор для обычных атак (например, царапина, удар)
# Защита: базовое сопротивление обычным атакам
#SP Atk: специальная атака, базовый модификатор для специальных атак (например, огненный взрыв, пузырьковый луч)
#SP Def: Базовое сопротивление урону от специальных атак
#Speed: определяет, какой покемон атакует первым в каждом раунде.

###### 3 Описание проблемы ####
# У каждого покемона есть тип, который мы можем выбрать в начале
# Попробуем проанализировать, какой тип лучше и для каких целей
