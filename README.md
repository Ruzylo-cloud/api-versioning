# API Versioning

Handle multiple API versions without code duplication.

```javascript
const router = new VersionedRouter();
router.v1.get('/users', handleV1);
router.v2.get('/users', handleV2);
```

Solves: Backwards compatibility, gradual migrations, client support.
License: MIT

---
Part of the [ferrow-toolkit](https://github.com/FerrowAI/ferrow-toolkit) collection · Sponsored by [Ferrow](https://ferrow.ai)
