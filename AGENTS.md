<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

- Keep the Isaro storefront at the index route and its catalog in a shared browser-safe module so pricing and WhatsApp order totals use a single source of truth.
- Use in-session shopping bag state and send final orders to the business through WhatsApp; no online payment or persistent customer account is represented.
- Define storefront styling and visual tokens in the global stylesheet and expose button treatments through the shared Button variants to keep the brand consistent.
