<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="380" viewBox="0 0 1200 380" fill="none" xmlns:c2pa="http://c2pa.org/manifest">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1200" y2="380" gradientUnits="userSpaceOnUse">
      <stop offset="0" stop-color="#050B18"/>
      <stop offset="0.45" stop-color="#0B1F4D"/>
      <stop offset="0.8" stop-color="#1546B8"/>
      <stop offset="1" stop-color="#0891B2"/>
    </linearGradient>
    <linearGradient id="nameGrad" x1="0" y1="0" x2="700" y2="0" gradientUnits="userSpaceOnUse">
      <stop offset="0" stop-color="#FFFFFF"/>
      <stop offset="0.6" stop-color="#E0F2FE"/>
      <stop offset="1" stop-color="#7DD3FC"/>
    </linearGradient>
    <linearGradient id="line" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#38BDF8" stop-opacity="0"/>
      <stop offset="0.5" stop-color="#38BDF8"/>
      <stop offset="1" stop-color="#38BDF8" stop-opacity="0"/>
    </linearGradient>
    <radialGradient id="orbA"><stop offset="0" stop-color="#38BDF8" stop-opacity="0.55"/><stop offset="1" stop-color="#38BDF8" stop-opacity="0"/></radialGradient>
    <radialGradient id="orbB"><stop offset="0" stop-color="#6366F1" stop-opacity="0.45"/><stop offset="1" stop-color="#6366F1" stop-opacity="0"/></radialGradient>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M40 0H0V40" stroke="#93C5FD" stroke-opacity="0.07" stroke-width="1"/>
    </pattern>
    <clipPath id="card"><rect x="760" y="70" width="360" height="240" rx="16"/></clipPath>
    <clipPath id="reveal"><rect x="60" y="0" width="0" height="380"><animate attributeName="width" from="0" to="760" dur="1.6s" begin="0.2s" fill="freeze" calcMode="spline" keySplines="0.2 0.8 0.2 1" keyTimes="0;1"/></rect></clipPath>
    <filter id="shadow" x="-20%" y="-20%" width="140%" height="150%"><feDropShadow dx="0" dy="18" stdDeviation="22" flood-color="#000" flood-opacity="0.45"/></filter>
    <style>
      .sans{font-family:'Segoe UI','Helvetica Neue',Arial,sans-serif}
      .mono{font-family:'SFMono-Regular',Consolas,'Liberation Mono',Menlo,monospace}
      @keyframes float{0%,100%{transform:translateY(0)}50%{transform:translateY(-10px)}}
      @keyframes twinkle{0%,100%{opacity:.15}50%{opacity:.9}}
      @keyframes caret{0%,49%{opacity:1}50%,100%{opacity:0}}
      @keyframes sweep{0%{transform:translateX(-700px)}100%{transform:translateX(1300px)}}
      @keyframes fadeUp{0%{opacity:0;transform:translateY(14px)}100%{opacity:1;transform:translateY(0)}}
      .float{animation:float 6s ease-in-out infinite}
      .tw{animation:twinkle 3s ease-in-out infinite}
      .caret{animation:caret 1s steps(1) infinite}
      .sweep{animation:sweep 5s linear infinite}
      .f1{animation:fadeUp .9s .1s both}
      .f2{animation:fadeUp .9s .5s both}
      .f3{animation:fadeUp .9s .9s both}
      .f4{animation:fadeUp .9s 1.3s both}
    </style>
  </defs>

  <!-- background -->
  <rect width="1200" height="380" rx="20" fill="url(#bg)"/>
  <rect width="1200" height="380" rx="20" fill="url(#grid)"/>

  <!-- glowing orbs -->
  <circle r="220" fill="url(#orbA)"><animate attributeName="cx" values="980;1060;980" dur="12s" repeatCount="indefinite"/><animate attributeName="cy" values="60;130;60" dur="12s" repeatCount="indefinite"/></circle>
  <circle r="260" fill="url(#orbB)"><animate attributeName="cx" values="120;220;120" dur="14s" repeatCount="indefinite"/><animate attributeName="cy" values="340;280;340" dur="14s" repeatCount="indefinite"/></circle>

  <!-- stars -->
  <g fill="#E0F2FE">
    <circle class="tw" cx="90"  cy="60"  r="1.6"/>
    <circle class="tw" style="animation-delay:.6s" cx="310" cy="38"  r="1.2"/>
    <circle class="tw" style="animation-delay:1.2s" cx="560" cy="330" r="1.5"/>
    <circle class="tw" style="animation-delay:1.8s" cx="700" cy="46"  r="1.3"/>
    <circle class="tw" style="animation-delay:.3s" cx="1130" cy="40" r="1.6"/>
    <circle class="tw" style="animation-delay:2.1s" cx="1160" cy="250" r="1.2"/>
    <circle class="tw" style="animation-delay:1.5s" cx="450" cy="352" r="1.2"/>
    <circle class="tw" style="animation-delay:.9s" cx="40" cy="200" r="1.3"/>
  </g>

  <!-- left content -->
  <g class="sans">
    <g class="f1">
      <rect x="60" y="76" width="34" height="3" rx="1.5" fill="#38BDF8"/>
      <text x="104" y="84" fill="#7DD3FC" font-size="14" font-weight="600" letter-spacing="4">FULL STACK DEVELOPER</text>
    </g>
    <text class="f2" x="60" y="164" fill="url(#nameGrad)" font-size="58" font-weight="800" letter-spacing="-1">Muhammad Sayem</text>
    <text class="f2" x="60" y="228" fill="url(#nameGrad)" font-size="58" font-weight="800" letter-spacing="-1">Hossain</text>
    <text class="f3" x="60" y="274" fill="#BAE6FD" font-size="19" font-weight="400" letter-spacing="0.4">Software Engineer  <tspan fill="#38BDF8">|</tspan>  UI/UX Designer  <tspan fill="#38BDF8">|</tspan>  Digital Creator</text>
    <g class="f4">
      <rect x="60" y="302" width="150" height="34" rx="17" fill="#FFFFFF" fill-opacity="0.08" stroke="#7DD3FC" stroke-opacity="0.35"/>
      <circle cx="82" cy="319" r="4" fill="#38BDF8"><animate attributeName="opacity" values="1;.25;1" dur="2s" repeatCount="indefinite"/></circle>
      <text x="96" y="324" fill="#E0F2FE" font-size="13" font-weight="600" letter-spacing="0.5">Bangladesh</text>
      <rect x="222" y="302" width="206" height="34" rx="17" fill="#FFFFFF" fill-opacity="0.08" stroke="#7DD3FC" stroke-opacity="0.35"/>
      <text x="245" y="324" fill="#E0F2FE" font-size="13" font-weight="600" letter-spacing="0.5">SaaS  /  AI  /  Automation</text>
    </g>
  </g>

  <!-- code card -->
  <g class="float" filter="url(#shadow)">
    <rect x="760" y="70" width="360" height="240" rx="16" fill="#0A1224" fill-opacity="0.82" stroke="#7DD3FC" stroke-opacity="0.25"/>
    <g clip-path="url(#card)">
      <rect x="760" y="70" width="360" height="40" fill="#FFFFFF" fill-opacity="0.05"/>
    </g>
    <circle cx="784" cy="90" r="5" fill="#475569"/>
    <circle cx="802" cy="90" r="5" fill="#475569"/>
    <circle cx="820" cy="90" r="5" fill="#475569"/>
    <text class="mono" x="940" y="94" fill="#64748B" font-size="12" text-anchor="middle">developer.js</text>
    <g class="mono" font-size="14">
      <text x="784" y="140"><tspan fill="#C084FC">const</tspan> <tspan fill="#7DD3FC">sayem</tspan> <tspan fill="#94A3B8">=</tspan> <tspan fill="#E2E8F0">{</tspan></text>
      <text x="804" y="166"><tspan fill="#93C5FD">role</tspan><tspan fill="#94A3B8">:</tspan> <tspan fill="#86EFAC">"Full Stack"</tspan><tspan fill="#94A3B8">,</tspan></text>
      <text x="804" y="192"><tspan fill="#93C5FD">stack</tspan><tspan fill="#94A3B8">:</tspan> <tspan fill="#E2E8F0">[</tspan><tspan fill="#86EFAC">"Laravel"</tspan><tspan fill="#94A3B8">,</tspan> <tspan fill="#86EFAC">"React"</tspan><tspan fill="#E2E8F0">]</tspan><tspan fill="#94A3B8">,</tspan></text>
      <text x="804" y="218"><tspan fill="#93C5FD">focus</tspan><tspan fill="#94A3B8">:</tspan> <tspan fill="#86EFAC">"SaaS + AI"</tspan><tspan fill="#94A3B8">,</tspan></text>
      <text x="804" y="244"><tspan fill="#93C5FD">status</tspan><tspan fill="#94A3B8">:</tspan> <tspan fill="#86EFAC">"Building"</tspan></text>
      <text x="784" y="270"><tspan fill="#E2E8F0">}</tspan><tspan fill="#94A3B8">;</tspan></text>
      <rect class="caret" x="808" y="257" width="8" height="15" fill="#38BDF8"/>
    </g>
  </g>

  <!-- bottom sweep line -->
  <rect x="60" y="360" width="1080" height="1.5" fill="#FFFFFF" fill-opacity="0.08"/>
  <g clip-path="url(#none)"><rect class="sweep" x="0" y="359" width="400" height="3" fill="url(#line)"/></g>
<metadata><c2pa:manifest>AAAWgmp1bWIAAAAeanVtZGMycGEAEQAQgAAAqgA4m3EDYzJwYQAAABZcanVtYgAAAEdqdW1kYzJtYQARABCAAACqADibcQN1cm46YzJwYTo2OTMxZTdjMy1mNDc1LTQ5YWMtOGZjNy04M2MxYmIwMzMyM2EAAAADl2p1bWIAAAApanVtZGMyYXMAEQAQgAAAqgA4m3EDYzJwYS5hc3NlcnRpb25zAAAAALxqdW1iAAAARGp1bWRjYm9yABEAEIAAAKoAOJtxE2MycGEuaW5ncmVkaWVudC52MwAAAAAYYzJzaM8BGSH2R7CJ9YbTJT5NxfsAAABwY2JvcqNpZGM6Zm9ybWF0bWltYWdlL3N2Zyt4bWxqaW5zdGFuY2VJRHgseG1wOmlpZDpkZDM4OGZmYi05ODhhLTQwZGEtOTdhMC0yODJlMTQwZWQzZGRscmVsYXRpb25zaGlwaHBhcmVudE9mAAAB4mp1bWIAAABBanVtZGNib3IAEQAQgAAAqgA4m3ETYzJwYS5hY3Rpb25zLnYyAAAAABhjMnNoEGCM/daBOQPRUgCbWdNSQgAAAZljYm9yomdhY3Rpb25zgqJmYWN0aW9ua2MycGEub3BlbmVkanBhcmFtZXRlcnOha2luZ3JlZGllbnRzgaJjdXJseC1zZWxmI2p1bWJmPWMycGEuYXNzZXJ0aW9ucy9jMnBhLmluZ3JlZGllbnQudjNkaGFzaFggobiUSCAKfzBD4SHlcKSGHQUgx+mzkMiapoAnXH9sCj+kZmFjdGlvbngdY29tLmFudGhyb3BpYy5jbGF1ZGUucHJvdmlkZWRqcGFyYW1ldGVyc6F4H2NvbS5hbnRocm9waWMub3JpZ2luLWNvbmZpZGVuY2VndW5rbm93bmtkZXNjcmlwdGlvbnhmQ2xhdWRlIHByb3ZpZGVkIHRoaXMgZmlsZSBhdCB0aGUgcmVxdWVzdCBvZiBhIHVzZXIgYW5kIG1heSBoYXZlIGNyZWF0ZWQgb3IgbW9kaWZpZWQgdGhlIGZpbGUgY29udGVudHMubXNvZnR3YXJlQWdlbnShZG5hbWVmQ2xhdWRlcmFsbEFjdGlvbnNJbmNsdWRlZPUAAADIanVtYgAAAEBqdW1kY2JvcgARABCAAACqADibcRNjMnBhLmhhc2guZGF0YQAAAAAYYzJzaPPlOvBtBH1LsiD7ezXOf9IAAACAY2JvcqVjYWxnZnNoYTI1NmNwYWRMAAAAAAAAAAAAAAAAZGhhc2hYIDInszduSwkRivKmS05apL5kdDfMJlXb4xQAhXc68W9rZG5hbWVuanVtYmYgbWFuaWZlc3RqZXhjbHVzaW9uc4GiZXN0YXJ0GR4CZmxlbmd0aBkeBAAAAj5qdW1iAAAAJ2p1bWRjMmNsABEAEIAAAKoAOJtxA2MycGEuY2xhaW0udjIAAAACD2Nib3KlY2FsZ2ZzaGEyNTZpc2lnbmF0dXJleE1zZWxmI2p1bWJmPS9jMnBhL3VybjpjMnBhOjY5MzFlN2MzLWY0NzUtNDlhYy04ZmM3LTgzYzFiYjAzMzIzYS9jMnBhLnNpZ25hdHVyZWppbnN0YW5jZUlEeCx4bXA6aWlkOjQ5ZmI5Y2M0LTFkMjEtNDkwYy04NzRkLTM4NTY3NTY5NTJlNXJjcmVhdGVkX2Fzc2VydGlvbnODomN1cmx4LXNlbGYjanVtYmY9YzJwYS5hc3NlcnRpb25zL2MycGEuaW5ncmVkaWVudC52M2RoYXNoWCChuJRIIAp/MEPhIeVwpIYdBSDH6bOQyJqmgCdcf2wKP6JjdXJseCpzZWxmI2p1bWJmPWMycGEuYXNzZXJ0aW9ucy9jMnBhLmFjdGlvbnMudjJkaGFzaFggl75y/YsVjpj5T/WiUbdBU8mfTMH/Ta8L4uyNFSNXPZKiY3VybHgpc2VsZiNqdW1iZj1jMnBhLmFzc2VydGlvbnMvYzJwYS5oYXNoLmRhdGFkaGFzaFggQOFTMRQUJw8Jvl3houVpKb4zUqw5EFiAFnkgOHvvn6p0Y2xhaW1fZ2VuZXJhdG9yX2luZm+jZG5hbWVvQW50aHJvcGljIEZpbGVzZ3ZlcnNpb25lMS4wLjBrc3BlY1ZlcnNpb25lMi40LjAAABA4anVtYgAAAChqdW1kYzJjcwARABCAAACqADibcQNjMnBhLnNpZ25hdHVyZQAAABAIY2JvctKEWQISogEmGCFZAgowggIGMIIBjaADAgECAhRA5aAK7sI50L64g/oGQgU9Z1UTADAKBggqhkjOPQQDAzBJMRcwFQYDVQQKEw5BbnRocm9waWMsIFBCQzEuMCwGA1UEAxMlQW50aHJvcGljIENvbnRlbnQgQ3JlZGVudGlhbHMgUm9vdCBDQTAeFw0yNjA4MDcxODQzNTZaFw0yODA4MDYxOTQzNTZaMEQxFzAVBgNVBAoTDkFudGhyb3BpYywgUEJDMSkwJwYDVQQDEyBBbnRocm9waWMgQ2xhdWRlIENvbnRlbnQgU2lnbmluZzBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABJh6CmvLUBgFFNU0vUKlOVtE6djd17L5SuwX0LemFisBM3dkd/3cyjxFA3Qo5S46fX0/ihY0VZ7mfb9KF703t5OjWDBWMA4GA1UdDwEB/wQEAwIHgDAVBgNVHSUEDjAMBgorBgEEAYPoXgIBMAwGA1UdEwEB/wQCMAAwHwYDVR0jBBgwFoAUzlHiBIFOZFsj+OPEz5o+nMHXXMIwCgYIKoZIzj0EAwMDZwAwZAIwMXMdFJ4BetLLVY7ORuE9noqbbAZOZn/aArXyTwFAZfKrPzxF2vPoJNf1+UCdg1XGAjBwX1zd9WGqYkqmL5SFqw1QySjr1zJfpJM9+1rdDwSPLMOPOjKuiXjoU/pUUeG9RwmhY3BhZFkNngAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAPZYQKMO1O9yfcUBdwqJ1Ys0PUFszj2wQ1FNklRUat6hTrixPYtUEm1gwV898Zb087lRwAb3NlOtSDsHBBs+rbynwIs=</c2pa:manifest></metadata></svg>
