<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/wordmark-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/wordmark-light.png">
    <img alt="wasaybuilds" src="assets/wordmark-light.png" width="360">
  </picture>
</p>

<p align="center">
  Full stack engineer in Lahore. I build CRM and SaaS platforms, connect them to the systems clients already run, and lately I study how AI coding agents fake "done".
</p>

<p align="center">
  <a href="https://wasaybuilds.hashnode.dev">Blog</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/wasaybuilds">LinkedIn</a> &nbsp;·&nbsp;
  <a href="https://wasay-one.vercel.app">Portfolio</a> &nbsp;·&nbsp;
  <a href="mailto:wasaya670@gmail.com">Email</a>
</p>

<br>

## Building now

### [Proof of Done](https://github.com/wasaybuilds/proof-of-done)

[![npm](https://img.shields.io/npm/v/proof-of-done?style=flat-square&color=34d399&label=npm)](https://www.npmjs.com/package/proof-of-done)
[![downloads](https://img.shields.io/npm/dm/proof-of-done?style=flat-square&color=34d399)](https://www.npmjs.com/package/proof-of-done)
[![license](https://img.shields.io/github/license/wasaybuilds/proof-of-done?style=flat-square&color=34d399)](https://github.com/wasaybuilds/proof-of-done/blob/main/LICENSE)

An open source check that stops a coding agent from saying it's finished after it has deleted, skipped or gutted tests. In Claude Code it runs as a hook: when the agent tries to stop, it compares everything changed since the session started and sends the agent back if a test was tampered with.

Plain code, no model in the loop, so it costs next to nothing to run.

```bash
npm install --save-dev proof-of-done
npx proof-of-done install claude-code
```

<br>

## Writing

I'm collecting real, documented cases of agents faking "done", plus build logs on the tool itself.

- [The agent said "all tests pass." The test folder was 70% smaller.](https://wasaybuilds.hashnode.dev/the-agent-said-all-tests-pass-the-test-folder-was-70-smaller)
- [I tested my AI agent guardrail on a real agent. It made Claude undo my own request.](https://wasaybuilds.hashnode.dev/i-tested-my-ai-agent-guardrail-on-a-real-agent-it-made-claude-undo-my-own-request)

<br>

## Open source

**[TanStack Query #11188](https://github.com/TanStack/query/pull/11188)** · merged

The `no-unstable-deps` lint rule flagged built in method names as unstable dependencies, because its lookup tables inherited from `Object.prototype`. Fixed with prototype free dictionaries and regression tests across all three affected paths.

**[Rivet agentos #1908](https://github.com/rivet-dev/agentos/pull/1908)** · merged

`realpathSync` broke out of its resolution loop on any unexpected errno and returned the partially resolved prefix, so a permission failure came back looking like a valid parent directory. Now it fails the way it should.

<br>

## Shipped

Three years at Hatzs Dimensions building four CRM products across four industries. Two of them later became their own companies.

**Befer.** AI CRM for field service businesses. Scheduling, dispatch, quoting and Stripe invoicing, plus a service that turns a technician's voice note into a validated job record. I onboarded the first nine businesses myself and it has processed over 4,000 jobs in production.

**Voice and chat agents.** Twilio and ElevenLabs, with conversation state shared across channels so a phone call picks up where the website chat left off. The latency budget drove most of the design.

**Integrations.** Lender APIs, scheduling and inventory systems, Stripe, Square and a Bank of America payment gateway. Webhooks, retries, and reconciling the transactions that fail.

<br>

## Stack

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,py,nodejs,express,react,nextjs,redux,tailwind,graphql&perline=10" alt="languages and frameworks">
</p>
<p>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,aws,docker,githubactions,vercel,jest,linux&perline=10" alt="data and infrastructure">
</p>

<br>

<p align="center">
  <sub>Open to remote work. If an agent has ever faked "done" on you, I'd like to hear about it.</sub>
</p>
