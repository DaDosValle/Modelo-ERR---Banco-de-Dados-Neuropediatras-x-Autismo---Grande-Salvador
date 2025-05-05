Projeto: Banco de Dados para Atendimento em Neuropediatria e Autismo — Grande Salvador


Contexto
O crescente número de crianças diagnosticadas com Transtorno do Espectro Autista (TEA) e outras condições neurológicas exige uma rede de suporte médico mais eficiente e acessível. Salvador, Lauro de Freitas e Simões Filho são regiões com demanda significativa por neuropediatras, tanto na rede pública quanto particular. No entanto, informações descentralizadas dificultam o acesso das famílias e o gerenciamento pelas clínicas.

Este projeto visa modelar um banco de dados robusto que centralize e organize dados relevantes para facilitar o atendimento, agendamento, cobertura por planos de saúde e análise de distribuição de profissionais da área de neuropediatria voltados ao autismo na Grande Salvador.

Objetivo
Desenvolver um esquema de banco de dados relacional que:

Mapeie profissionais de neuropediatria por localização, especialidade e planos de saúde aceitos.

Cadastre clínicas públicas e privadas, possibilitando cruzamento de dados com municípios.

Registre informações de pacientes, seus agendamentos e a cobertura de convênios.

Sirva como base para criação de sistemas de busca, filtragem e análise geográfica.

Entidades principais
Profissional (CRM, especialidade, convênios aceitos)

Clínica (nome, CNPJ, tipo — pública ou privada)

Atendimento (data, profissional, clínica, paciente)

Município (nome, região)

Convênio (nome do plano, tipo de cobertura)

Tecnologias sugeridas
Modelagem com MySQL

Diagramas com Canva e MySQL Workbeach



Aplicações futuras
Desenvolvimento de uma plataforma de busca por especialistas em TEA na região (eu mesmo pretendo criar)

Ferramenta de apoio à secretarias de saúde e clínicas para gestão de agendamentos (vou divulgar banco de dados e análises futuras)

Painel BI para análise de demanda x oferta de serviços em neuropediatria (publicarei na web para auxiliar familiares de autistas e outros).

Criado por: Fernando M. do Valle (https://www.linkedin.com/in/fernando-m-do-valle-b653a7349/)
