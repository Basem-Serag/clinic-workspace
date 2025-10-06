# Clinic Workspace (Angular 20 + Nx 21)

## Apps
- `apps/angular-lab` – learning routes (signals, rxjs, forms)
- `apps/clinic` – SSR-enabled clinic app (MVP: Auth, Patients, Appointments)

## Quick start
```bash
npm install
npx nx serve angular-lab      # http://localhost:4200
npx nx serve clinic           # SSR dev server
npx nx test angular-lab
npx nx e2e angular-lab-e2e
