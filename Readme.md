# Tushar Khandelwal

Engineer who loves solving problems. 

[LinkedIn](https://www.linkedin.com/in/tushar-khandelwal-640b5a288) · [X](https://x.com/Beluga_69_69)

## Now

-> Contributing to Better Auth  
-> Exploring low level programming  
-> Building Redis from scratch in C++  

## Experience

**Rikrol** · Software Engineer (Freelance)

- Built a schema driven static analyzer for a custom XML based DSL, parsing templates into an AST and validating **50+ components** against a typed JSON schema.
- Implemented a structural type system with union types, inheritance resolution and scoped variable tracking, catching input and output mismatches across nested types at compile time.
- Designed LSP compatible diagnostics with exact line and column positions, integrated with Monaco Editor as a language server.
- Built frontend templates on top of the DSL.

**CodeHelp** · Problem Setter Intern

- Authored **50+ DSA problems** end to end, with statements, editorials and optimized C++ solutions.
- Built test suites for **500+ problems** with 100 to 1000 cases each, covering boundaries, large inputs and adversarial cases.
- Debugged I/O handling, constraint violations and judge errors across the problem pipeline.

## Projects

<table>
<tr>
<th>Project</th>
<th>What it does</th>
<th>Stack</th>
</tr>
<tr>
<td><a href="https://github.com/Tushar-Khandelwal-2004/Secure-Pixel">SecurePixel</a></td>
<td>Image ownership and duplicate detection API.
<ul>
<li>Architected a dual service platform with Express and FastAPI behind an Nginx reverse proxy, with Prisma ORM, Redis rate limiting and Docker Compose orchestration.</li>
<li>Built a 3 layer detection pipeline combining invisible DWT-DCT-SVD watermarking, perceptual hash Hamming search and CLIP embedding semantic search.</li>
<li>Achieved <b>95.6% detection</b> across 31 attack types, outperforming ImageHash (80.7%), SSIM (79.8%) and OpenCV template matching (77.7%).</li>
</ul>
</td>
<td>TypeScript · Express · FastAPI · PostgreSQL · Redis · Docker</td>
</tr>
<tr>
<td><a href="https://github.com/Tushar-Khandelwal-2004/Vistara">Vistara</a></td>
<td>Real time multi-user collaborative whiteboard.
<ul>
<li>Built Zod validated WebSocket events with room membership checks and Prisma persistence, enforcing authorized drawing writes across sessions.</li>
<li>Optimized PostgreSQL canvas history retrieval with composite indexes on roomId and id for ordered, efficient shape loading at scale.</li>
<li>Hardened Next.js canvas rendering with pointer capture, lifecycle cleanup and race safe history buffering, eliminating duplicate shape renders on concurrent updates.</li>
</ul>
</td>
<td>Turborepo · Next.js · Express · PostgreSQL · Prisma · TailwindCSS</td>
</tr>
</table>

## Open source

**Merged PRs**

<table>
<tr>
<th>Repository</th>
<th>PR</th>
<th>What it fixes</th>
</tr>
<tr>
<td rowspan="2"><a href="https://github.com/better-auth/better-auth">better-auth</a></td>
<td><a href="https://github.com/better-auth/better-auth/pull/10336">#10336</a></td>
<td>Patched request clone failures in auth callbacks via <code>safeCloneRequest</code>, preventing errors on disturbed request bodies.</td>
</tr>
<tr>
<td><a href="https://github.com/better-auth/better-auth/pull/10053">#10053</a></td>
<td>Fixed headerless session checks in Astro by narrowing <code>requireHeaders</code> to non-nullable endpoints only.</td>
</tr>
<tr>
<td rowspan="2"><a href="https://github.com/CopilotKit/CopilotKit">CopilotKit</a></td>
<td><a href="https://github.com/CopilotKit/CopilotKit/pull/5603">#5603</a></td>
<td>Handled empty tool result content in the web inspector.</td>
</tr>
<tr>
<td><a href="https://github.com/CopilotKit/CopilotKit/pull/5099">#5099</a></td>
<td>Resolved unstyled Streamdown markdown in non-Tailwind apps via scoped CSS fallback selectors under <code>[data-copilotkit]</code>.</td>
</tr>
<tr>
<td><a href="https://github.com/cashew-labs/libretto">libretto</a></td>
<td><a href="https://github.com/cashew-labs/libretto/pull/456">#456</a></td>
<td>Added TypeScript checking for benchmarks.</td>
</tr>
</table>

**Open PRs**

<table>
<tr>
<th>Repository</th>
<th>PR</th>
<th>What it does</th>
</tr>
<tr>
<td rowspan="8"><a href="https://github.com/better-auth/better-auth">better-auth</a></td>
<td><a href="https://github.com/better-auth/better-auth/pull/11593">#11593</a></td>
<td>Support Lynx regex compatibility in core.</td>
</tr>
<tr>
<td><a href="https://github.com/better-auth/better-auth/pull/11438">#11438</a></td>
<td>Reject mismatched OIDC issuers in SSO.</td>
</tr>
<tr>
<td><a href="https://github.com/better-auth/better-auth/pull/11338">#11338</a></td>
<td>Allow localhost subdomains over HTTP in MCP.</td>
</tr>
<tr>
<td><a href="https://github.com/better-auth/better-auth/pull/11320">#11320</a></td>
<td>Defer OAuth provider resource seeding until the Drizzle schema is ready.</td>
</tr>
<tr>
<td><a href="https://github.com/better-auth/better-auth/pull/10452">#10452</a></td>
<td>Return mapped WebAuthn error codes for passkeys.</td>
</tr>
<tr>
<td><a href="https://github.com/better-auth/better-auth/pull/10349">#10349</a></td>
<td>Document form-encoded request bodies in OpenAPI.</td>
</tr>
<tr>
<td><a href="https://github.com/better-auth/better-auth/pull/10106">#10106</a></td>
<td>Handle async auth init rejections.</td>
</tr>
<tr>
<td><a href="https://github.com/better-auth/better-auth/pull/10079">#10079</a></td>
<td>Lazily initialize request state holders.</td>
</tr>
<tr>
<td rowspan="2"><a href="https://github.com/cashew-labs/libretto">libretto</a></td>
<td><a href="https://github.com/cashew-labs/libretto/pull/461">#461</a></td>
<td>Lazy-load the Asciihedron debug pane.</td>
</tr>
<tr>
<td><a href="https://github.com/cashew-labs/libretto/pull/457">#457</a></td>
<td>Reuse middleware session state for execution.</td>
</tr>
<tr>
<td rowspan="3"><a href="https://github.com/daytonaio/daytona">daytona</a></td>
<td><a href="https://github.com/daytonaio/daytona/pull/5049">#5049</a></td>
<td>Serialize X11 screenshot access in the computer-use package.</td>
</tr>
<tr>
<td><a href="https://github.com/daytonaio/daytona/pull/5041">#5041</a></td>
<td>Add a TealTiger governed sandbox guide to the docs.</td>
</tr>
<tr>
<td><a href="https://github.com/daytonaio/daytona/pull/4933">#4933</a></td>
<td>Allow selecting toast text in the dashboard.</td>
</tr>
<tr>
<td><a href="https://github.com/knative/func">knative/func</a></td>
<td><a href="https://github.com/knative/func/pull/3925">#3925</a></td>
<td>Let KEDA functions scale to zero.</td>
</tr>
</table>

## Competitive programming

**1500+ problems solved** · [Codeforces](https://codeforces.com/profile/Tushar_Khandelwal) Specialist · [CodeChef](https://www.codechef.com/users/tushar8527) 4 star · [LeetCode](https://leetcode.com/u/Tushar-Khandelwal-2004/) · AtCoder

## Recognition

-> Part of the first ever batch of Dell Aspire Scholars, 80 students selected across India.  
-> Meta Hacker Cup Round 2 qualified.

## Stack

Not Bounded by any Stack!
