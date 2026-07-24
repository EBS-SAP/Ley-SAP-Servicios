mkdir Ley-SAP-Servicios
cd Ley-SAP-Servicios
git init

echo "# Proyecto Ley SAP en Servicios Públicos" > README.md


mkdir normatividad jurisprudencia casos-practicos tabla


echo "Artículos relevantes de la Ley 142 de 1994" > normatividad/Ley142-1994.md
echo "Resolución CREG 070 de 1998 y modificaciones" > normatividad/ResolucionCREG070-1998.md
echo "Concepto SSPD 674 de 2017" > normatividad/ConceptoSSPD674-2017.md

echo "Sentencia Consejo de Estado sobre suspensión" > jurisprudencia/ConsejoEstado-SentenciaSuspension.md
echo "Sentencia Corte Constitucional sobre silencio administrativo positivo" > jurisprudencia/CorteConstitucional-SilencioAdmPositivo.md

echo "Caso: suspensión por falta de pago" > casos-practicos/SuspensionPorFaltaDePago.md
echo "Caso: pago doble de factura" > casos-practicos/PagoDobleFactura.md

echo "| Competencia | No Competencia |" > tabla/CompetenciasVsNoCompetencias.md
echo "|-------------|----------------|" >> tabla/CompetenciasVsNoCompetencias.md
echo "| Negativa del contrato | Acuerdos de pago |" >> tabla/CompetenciasVsNoCompetencias.md
# Ley-SAP-Servicios
Repositorio con normativa, jurisprudencia y casos prácticos sobre Ley SAP y servicios públicos domiciliarios en Colombia
