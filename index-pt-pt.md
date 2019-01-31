---
title: 2019
lang: pt-PT
redirect_from:
  - /pt-pt/
---


O que está a acontecer?
=======================
Os sistemas de [DNS](https://pt.wikipedia.org/wiki/Domain_Name_System) actuais são lentos e ineficientes devido aos esforços existentes para 
adaptar alguns sistemas de DNS que já não se encontram em conformidade com padrões estabelecidas há duas décadas.

Para garantir uma maior sustentabilidade do sistema, está na hora de acabarmos com essas adaptações e de remediar os sistemas inconformados.
Esta alteração irá aumentar a eficiência da maioria das operações de DNS e permitirá às operadoras implementar novos mecanismos de protecção contra ataques [DDoS].

Os provedores de serviços e software de DNS [listados neste sítio](#apoiantes) concordaram em coordenar a remoção das adaptações para as implementações inconformadas de DNS dos seus softwares ou serviços, a partir de **1 de Fevereiro de 2019**. Esta alteração apenas irá afectar sítios a operar com softwares que não se encontram em conformidade.

Para mais informações, clica no grupo que te enquadres:

- [Sou um mero utilizador da Internet, não tenho domínios](#users)
- [Sou dono de um domínio](#domain-holders)
- [Sou um admnistrador de DNS](#dns-admins)
- [Sou um especialista em DNS (Desenvolvedor de Software DNS, pesquisador, etc.)](#experts)


<a name="users"></a>

Sou um mero utilizador da Internet
=================
Não tens que te preocupar, caso sejas um mero utilizador da Internet, que não possui qualquer nome de domínio. Estas alterações apenas te afectam indirectamente e não há nada que possas fazer. Obrigado pelo teu interesse nos [DNS]!


<a name="domain-holders"></a>


Sou Dono de um Domínio
=================
Caso sejas um dono de domínio, por favor, utiliza o formulário abaixo para verificares se o teu domínio se encontra preparado para as novas alterações. O resultado do teste irá incluir informação passo-a-passo do que poderá ter de fazer.

{% include checker.html lang=site.data.checker.pt-pt %}

De realçar que apenas precisas de validar uma única zona, no caso de teres múltiplas zonas no mesmo servidor ou conjunto de servidores. Ver [detalhe técnico dos testes](#test-details) para informação extra.

<a name="dns-admins"></a>

Sou um Administrador de DNS
======================
O impacto da alteração agendada para o lado do cliente do DNS é descrito na secção para [Operadores de resolvedores de DNS] (#resolver-ops). Uma pequena percentagem de servidores autoritários podem exigir alterações [descritas abaixo](#auth-ops). Mais abaixo listamos [detalhes técnicos dos testes](#test-details) e [ferramentas para especialistas](#experts).

<a name="resolver-ops"></a>

Operadores de resolvedores de DNS
---------------------------------
--Por Traduzir--

<a name="auth-ops"></a>


Operadores do Servidor DNS
--------------------------
--Por Traduzir--

<a name="test-details"></a>


Detalhe dos Testes
------------------
--Por Traduzir--

<a name="mass-scanning"></a>


### Mass scanning
--Por Traduzir--

### Obtaining detailed test results
--Por Traduzir--

### Minimal working configuration
--Por Traduzir--


<a name="experts"></a>

I'm a DNS expert
==============

Desenvolvedores de software de DNS
----------------------------------

<a name="researchers"></a>

Pesquisadores
=============
Pesquisadores e outros envolvidos, tais como operadores de TLD, poderão se interessar pelos documentos abaixo:
 * [Estatísticas de conformidade EDNS](https://ednscomp.isc.org/) geradas pela [suite de testes de conformidade EDNS](https://gitlab.isc.org/isc-projects/DNS-Compliance-Testing) do ISC
 * [Apresentações](#presentations) abaixo
 * [Ferramentas](#tools) para avaliar o impacto real, etc.

 
<a name="presentations"></a>
 
Apresentações
=============

Geral
-----
* RIPE 77: Will your DNS break in 2019? [slides](https://ripe77.ripe.net/presentations/7-flagday.pdf), [video](https://ripe77.ripe.net/archives/video/2233/)
* LOADAYS 2018: Is Your DNS Server Up-To-Date [abstract](http://loadays.org/pages/dnsupdate.html), [slides](http://loadays.org/files/plexis-edns-workaround-removal-loadays-2018.pdf), [video](https://www.youtube.com/watch?v=OXbbH0ORmSY)
* UKNOF 2019: DNS Flag Day and Beyond [presentation](https://indico.uknof.org.uk/event/44/contributions/580/)


Técnico
-------
* DNS-OARC 29: A tale of five ccTLDs [abstract](https://indico.dns-oarc.net/event/29/contributions/662/), [slides](https://indico.dns-oarc.net/event/29/contributions/662/attachments/634/1063/EDNS_Flag_Day_-_OARC29.pdf), [video](https://youtu.be/rneu1lnJmUI?list=PLCAxS3rufJ1cOBd1D4K4QJFmLcSypixh3&t=2010)
* DNS-OARC 29: Estimating impact of the (E)DNS flag day [abstract](https://indico.dns-oarc.net/event/29/contributions/644/), [slides](https://indico.dns-oarc.net/event/29/contributions/644/attachments/632/1018/edns.pdf), [video](https://youtu.be/rneu1lnJmUI?list=PLCAxS3rufJ1cOBd1D4K4QJFmLcSypixh3&t=3001)
* DNS-OARC 28: First announcement [abstract](https://indico.dns-oarc.net/event/28/contributions/515/), [slides](https://indico.dns-oarc.net/event/28/contributions/515/attachments/490/799/Removing_EDNS_Workarounds.pdf), [video](https://www.youtube.com/watch?v=9YYH8JFH_bY&feature=youtu.be&t=5198)


Ferramentas
===========
Pesquisadores e outros envolvidos, tais como grandes operadores de DNS, poderão se interessar pelos documentos abaixo:

 * [ISC EDNS Compliance tester](https://ednscomp.isc.org/), [source code](https://gitlab.isc.org/isc-projects/DNS-Compliance-Testing) for testing all aspects of EDNS compliance
 * [EDNS zone scanner](https://gitlab.labs.nic.cz/knot/edns-zone-scanner/tree/master) for mass scanning and evaluation of real-world impact of the DNS flag day by CZ.NIC
 * [Testing EDNS Compatibility with dig](https://kb.isc.org/docs/edns-compatibility-dig-queries)
 * [DNSViz](http://dnsviz.net/)

 Por favor leia as respectivas metodologias antes de interpretar os dados. Em qualquer caso, não hesite em entrar em contacto com os autores das ferramentas usando os endereços acima.
 
 
Contactos
========

 * Comentários sobre este sítio podem ser adicionados no [repositório do dnsflagday](https://github.com/dns-violations/dnsflagday/issues) no Github
 * Comentários sobre os resultados de testes gerados por esse sítio ou pela [ferramenta ednscomp](https://ednscomp.isc.org/ednscomp) deve ser feitos no sítio do projecto [DNS Compliance Testing](https://gitlab.isc.org/isc-projects/DNS-Compliance-Testing).

 
Apoiantes
==========                                                                                    
{% include supporters.html %}

Leitura Adicional
=================
 * [Minimal EDNS compliance requirements](https://datatracker.ietf.org/doc/draft-spacek-edns-camel-diet/)
 * [“The DNS Camel”, or, the rise in DNS complexity](https://blog.powerdns.com/2018/03/22/the-dns-camel-or-the-rise-in-dns-complexit/)

[DDoS]: https://en.wikipedia.org/wiki/Denial-of-service_attack#Distributed_DoS_attack
[DNS]: https://en.wikipedia.org/wiki/Domain_Name_System
[RFC1035]: https://tools.ietf.org/html/rfc1035
[EDNS]: https://en.wikipedia.org/wiki/Extension_mechanisms_for_DNS
[RFC2671]: https://tools.ietf.org/html/rfc2671
[RFC6891]: https://tools.ietf.org/html/rfc6891