# Mandatory workflow for ushakov-finance.ru

## Owner and production
- Roman is the business owner. The assistant executes implementation, diagnostics, publication and verification. Do not delegate technical steps to Roman.
- Production is THIS repository: ushakovfinance-commits/ushakov-finance-site, branch main, GitHub Pages from /(root).
- Public address: https://ushakov-finance.ru/ . Roman confirmed it works on 2026-10-18 at 21:41 Moscow time.
- Preserve CNAME containing ushakov-finance.ru, .nojekyll, enabled Enforce HTTPS, relative asset paths and existing approved content/style.
- Sites project appgprj_6ad108e0fa548191870e450b37a79482 is the historical source, NOT the production publication target. Publishing only to Sites does not update the public domain.

## Required execution
1. Read this file and inspect current repository/deployment before acting. Resume from existing state; do not recreate the site, repository or infrastructure.
2. Discuss content/design changes in chat; do not change approved public content without Roman's agreement.
3. Prepare and test the agreed changes. If publication is not already authorized, present the concrete result and ask once whether to publish.
4. Once authorized, update this existing publication autonomously. Preserve CNAME and .nojekyll. Do not ask for repeated routine technical approvals.
5. Verify the successful Pages deployment, final public HTML and assets, HTTPS certificate validation, apex/www and HTTP-to-HTTPS redirects, mobile rendering and relevant interactions. Do not equate a provider success badge or a crawler 200 with universal visitor accessibility.
6. Fix ordinary implementation/deployment failures and continue. Report actual verified results and material unresolved limitations accurately. Never disable TLS validation to claim success.
7. Send Roman the public link and concise actual changes. Ask only for a genuine business decision, new access, expense, or consequential risk.

## Protected infrastructure
- Ordinary content/UI changes MUST NOT change DNS, hosting provider, registrar, custom-domain binding or certificate configuration.
- Do not switch back to Beget FreeHosting or chatgpt.site. Do not create duplicate sites or repositories.
- Beget remains registrar/DNS. Working records at acceptance: apex A 185.199.108.153 and 185.199.109.153; www A 185.199.108.153. Preserve MX, SPF, NS and autoconfig/autodiscover. Do not rewrite these merely because an isolated verification channel fails.
- No new paid services or obligations without explicit owner approval. Do not launch unrelated/heavy GitHub Actions. Use only the necessary existing Pages publication workflow.
- Reuse authenticated access. If sign-in really expires, use the secure in-chat browserAuth dialogue. Never request passwords/codes in chat or require manual cloud-browser operation.

## Continuity
Persistent operational note: Поиск работы ИИ/Порядок_правок_и_публикации_ushakov-finance.ru.md, Library ID libfile_a8784242cd308191bace15f6e44ea461. Read its latest version when further history is needed. It contains historical incident states; use the latest accepted production checkpoint, not obsolete rollback instructions.
