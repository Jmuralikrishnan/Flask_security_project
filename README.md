# Supply Chain Security Project

Implements Trivy scanning, Syft SBOM generation, Cosign signing and verification in GitHub Actions.

Workflow:
1. Build Docker image
2. Scan with Trivy
3. Generate SBOM with Syft
4. Push image
5. Sign using Cosign
6. Verify signature
