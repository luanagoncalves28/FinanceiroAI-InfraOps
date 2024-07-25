# 02. Terraform - Ambientes e Módulos

## Visão Geral

Este diretório "02. Terraform" é estruturado meticulosamente para abranger os componentes específicos da gestão de infraestrutura utilizando Terraform. Dividido em **Ambientes** e **Módulos**, ele serve como núcleo para a implantação e otimização de infraestrutura em nuvem, com uma abordagem específica para ambientes de desenvolvimento e produção, bem como a reusabilidade de módulos cruciais.

## Propósito do Diretório

Este diretório tem como objetivos:
- **Gerenciar Isoladamente os Ambientes**: Separar as configurações de 'Dev' e 'Prod' para minimizar riscos e otimizar o ciclo de vida do desenvolvimento.
- **Promover a Modularidade**: Armazenar módulos reutilizáveis de Terraform que podem ser aplicados em várias partes do projeto, facilitando a manutenção e escalabilidade.

## Público-Alvo

### Recrutadores Técnicos
Este diretório demonstra minhas habilidades em configurar e gerenciar infraestruturas complexas usando Terraform, com uma separação clara de ambientes e módulos, refletindo as melhores práticas de IaC e gestão de configurações.

### Recrutadores Não Técnicos
Aqui, a eficiência e a clareza da gestão de infraestrutura são expostas, mostrando como a automação e a organização podem trazer reduções significativas de custos e melhorias em compliance, fundamentais para o sucesso dos negócios.

### Profissionais da Área Técnicos
Explore a configuração detalhada dos ambientes e módulos, uma base ideal para discussões técnicas avançadas, colaboração e benchmarking de metodologias e soluções em infraestrutura como código.

### Profissionais da Área Não Técnicos
A estruturação em ambientes e módulos contribui para a eficiência operacional e alinhamento estratégico, facilitando a gestão de recursos e adaptabilidade às mudanças de mercado.

### Profissionais da Área de Negócio Interessados em Contratar
Veja como a implementação prática de Terraform em ambientes separados e módulos reutilizáveis pode resolver desafios de negócios complexos, melhorando o gerenciamento de riscos, compliance e eficiência operacional.

## Tecnologias e Metodologias Aplicadas

- **Terraform**: Utilizado para criar e gerenciar infraestruturas com eficiência e segurança.
- **Gerenciamento de Estado de Terraform**: Implementado para garantir a consistência e evitar conflitos entre diferentes ambientes.

## Estrutura do Diretório

- **02.1 Ambientes**: Contém configurações específicas para os ambientes de 'Dev' e 'Prod'.
  - `02.1.1 Dev`: Configurações para desenvolvimento.
  - `02.1.2 Prod`: Configurações para produção.
- **02.2 Módulos**: Armazena módulos reutilizáveis.
  - `02.2.1 Computação`: Módulos relacionados à computação.
  - `02.2.2 Rede`: Módulos relacionados à rede.

## Impacto nos Negócios

A estruturação eficiente em Terraform não só melhora o ciclo de desenvolvimento e a segurança das implementações, mas também proporciona uma gestão de infraestrutura que pode escalar com as necessidades do negócio, garantindo um retorno sobre o investimento através de melhorias em eficiência e compliance.

