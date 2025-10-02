---
title: API
type: docs
---

<div id="swagger-ui"></div>

<!-- CDN 스크립트 로드 -->
<link rel="stylesheet" href="https://unpkg.com/swagger-ui-dist/swagger-ui.css">
<script src="https://unpkg.com/swagger-ui-dist/swagger-ui-bundle.js"></script>
<script>
  window.addEventListener('DOMContentLoaded', function () {
    SwaggerUIBundle({
      url: '/api/openapi.json',   // 스펙 파일 경로
      dom_id: '#swagger-ui',
      deepLinking: true,
      presets: [SwaggerUIBundle.presets.apis],
      supportedSubmitMethods: [],
      layout: "BaseLayout",
    });
  });
</script>