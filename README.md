# Rota 12x60 — Gestor Automotivo, BlaBlaCar, Consignado & Estadia (Curitiba ↔ Joinville)

Aplicativo Android (`.apk`) e Web App 100% offline personalizado para cálculo e simulação financeira da rotina **Curitiba ↔ Joinville** na escala **12x12x12x60**.

## 📲 Download Direto do APK Android

👉 **[Baixar Rota-12x60-Peugeot208.apk (Release v1.0.0)](https://github.com/abiatarprado/rota-12x60-app/releases/latest)**

*(Basta abrir o link acima no celular Android, tocar em `Rota-12x60-Peugeot208.apk` em **Assets** e instalar).*

---

## ✨ Funcionalidades Incluídas

1. **Simulador Geral da Escala 12x12x12x60 (CWB ↔ Joinville)**:
   - Configurado com os parâmetros reais: **140 km por trecho** (Casa em Curitiba ↔ Batalhão em Joinville), **7,5 ciclos/mês** (15 trechos de estrada/mês), **Peugeot 208 Allure 2013** fazendo **12,3 km/l** com gasolina aditivada a **R$ 6,29/l**.
   - **Simulador de Caronas BlaBlaCar**: controle independente de ocupação média na Ida e na Volta (0 a 3 passageiros pagando R$ 40 cada + km de desvio), mostrando o ponto de equilíbrio exato da viagem.
2. **Troca de Carro & Comparador de Modais**:
   - Compara manter o **Peugeot 208 Allure 2013** contra:
     - **Trocar de Veículo** (com presets rápidos para *Hatch 1.0 Onix/HB20/Polo*, *Kwid/Mobi*, *1.0 Turbo*, *BYD Dolphin Mini Elétrico*, *Moto 250cc* ou qualquer modelo personalizado).
     - **Ônibus Rodoviário + Uber Local** (sem carro).
     - **Carona como Passageiro no BlaBlaCar + Uber Local** (sem carro).
   - Simula tanto **manter o consignado em folha (R$ 518,35/mês)** quanto **quitar as 79 parcelas restantes usando o valor da venda do Peugeot**.
3. **Comparador dos 4 Cenários de Estadia em Joinville (Descanso de 12h)**:
   - **(1) Dormir no Batalhão** (R$ 0/mês)
   - **(2) Alugar Kitnet / Quarto Fixo em Joinville** (aluguel + contas + deslocamento Batalhão ↔ Imóvel)
   - **(3) Pernoite Avulso por Escala** (Hotel / Airbnb / Pousada nas 7,5 noites do mês)
   - **(4) Mudar para Joinville** (invertendo a rota: morar perto do Batalhão e ir para Curitiba apenas nas folgas de 60h escolhidas)
4. **Gestão Completa do Consignado Bradesco (Contrato 05009801)**:
   - Contém todas as **120 parcelas** do relatório de `25/03/2026` (41 pagas até `28/10/2026`, equivalente a `40/119` pós-portabilidade, e **79 restantes** de `R$ 518,35` até `28/05/2033`).
   - Mostra o valor presente para quitação tanto pela **soma direta da tabela (R$ 23.854,97)** quanto pela **curva atualizada para 79 parcelas restantes (R$ 26.110,97)**.
   - **Simulador de Amortização Extra (De trás pra frente)**: digite qualquer valor em R$ e veja quantas parcelas finais (`Inversa 1, 2, 3...`) você elimina e quanto economiza de juros.
5. **Diário Real de Viagens (BlaBlaCar) & Histórico de Manutenções**:
   - Cadastre cada viagem feita (data, sentido, km, consumo, quantidade de passageiros 0–3, valor cobrado e pedágio) e importe a média real direto para o simulador.
   - Cadastre todas as manutenções realizadas no Peugeot 208 e acompanhe o custo real por km e rateio mensal.
   - Salvamento automático no aparelho (`localStorage`) + **Exportação e Restauração de Backup (`.json`)**.
