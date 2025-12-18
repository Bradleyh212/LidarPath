# LidarPath

Lightweight LiDAR → Cloud → Viewer pipeline.  
A minimal version of a road-mapping system for future drone integration.

## Features (MVP)
- Simulated LiDAR scan generator (Python)
- Upload scans to AWS S3
- Lambda processing step (convert angles/distances → point cloud)
- Web dashboard to visualize processed points

## Tech Stack
- Python (collector + Lambda)
- AWS: S3, Lambda, IAM
- React + MapLibre (frontend)
- Terraform (infra)

## Roadmap
1. Simulated LiDAR data ingestion
2. AWS S3 → Lambda pipeline
3. Vectorization of point cloud
4. Frontend point cloud viewer
5. Add real LiDAR hardware later
