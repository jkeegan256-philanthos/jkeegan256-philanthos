Nursing Home Records
nursinghomerecords.org
A static mirror of the CMS Provider Data Catalog nursing homes theme.
Every certified nursing home in the United States, the ownership
disclosures filed for it, and the deficiency, penalty, and survey
records CMS publishes, shown as filed. Rebuilt monthly from the CMS
source zip. No calculations, no rankings, no editorial layer.
�
Load image
Looking through the repository
PROJECT.md is the charter: purpose, principles, declined scope,
and a decision log that records what was shipped and then reversed,
with the reasoning at full length.
ADAPTATION.md lists which parts are specific to this dataset,
for anyone adapting the pipeline to another one.
ci.yml holds the checks that run on every change, including a
browser that loads the built site and fails on any request to
another host.
Next.js static export, DuckDB and DuckDB-WASM, GitHub Actions, GitHub
Pages. No servers, no database, no third-party requests.
