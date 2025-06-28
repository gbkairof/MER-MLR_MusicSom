# MER-MLR_MusicSom

# 🎧 Musicsom – Aplicativo de Descoberta Musical Personalizada

Este projeto foi desenvolvido como parte da disciplina de *Banco de Dados, na **Faculdade de Tecnologia Pastor Enéas Tognini - Ipiranga (FATEC Ipiranga), com o objetivo de propor uma nova abordagem para recomendações musicais, focada **nas características sonoras* dos álbuns e não em padrões de consumo ou preferências por artista/gênero.

## 🧠 Objetivo
Criar a modelagem de dados de um sistema de recomendação musical centrado nas preferências técnicas e sensoriais do usuário, rompendo com a lógica dos algoritmos tradicionais que reforçam zonas de conforto.

---

## 📌 Estrutura do Projeto

### 🔹 Modelo Conceitual (MER)
- Entidades: Usuário, Pesquisa, Álbum, Banda_Artista, Gênero, Idioma, Características_Musicais, entre outras.
- Especializações: Instrumento, BPM, Vocais, Atmosfera
- Entidades associativas como Pesquisa_Características_Selecionadas e Álbum_Características garantem a flexibilidade da consulta.

### 🔹 Modelo Lógico Relacional (MLR)
- Estrutura de tabelas normalizadas com chaves primárias e estrangeiras.
- Relacionamentos 1:N e N:M com regras claras de integridade.
- Suporte a especialização com FKs ligando as subclasses à superclasse Características_Musicais.

---

## 🧪 Funcionamento da Pesquisa

Durante uma busca, o usuário seleciona:
- *Instrumentos* (e suas classes/fonte sonora)
- *BPM predominante*
- *Presença e tipo de vocais*
- *Atmosfera desejada*

O sistema cruza essas preferências com os dados armazenados e recomenda álbuns alinhados, *sem considerar gênero musical ou artista*.

---

## 📊 Considerações Técnicas

- Modelo desenvolvido com base em conceitos de banco de dados relacional e modelagem conceitual.
- Permite escalabilidade e integração com serviços futuros (ex: APIs externas).
- Estrutura modular voltada para experiências personalizadas.

---

## 👥 Autores

- Gabriel Novelli Kairof  
- Leandro Costa Belfor  

---

## 📚 Professora Responsável

*Ana Travassos Ichihara*  
Disciplina: Banco de Dados

---

## 🏷 Tecnologias Relevantes
- Modelagem Entidade-Relacionamento (MER)
- Modelo Lógico Relacional (MRL)
- Normalização de Banco de Dados
