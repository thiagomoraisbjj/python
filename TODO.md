# TODO: Jiu-Jitsu SaaS Development

## Plan Steps (from approved plan)

### 1. Project Skeleton (70% complete)
- [x] Create branch `blackboxai/jiu-jitsu-saas`
- [ ] Create `jiu-jitsu-saas/` directory structure
- [ ] Backend: package.json, nest cli init
- [ ] Frontend: Vite React TS + Tailwind
- [ ] Docker-compose.yml

### 2. Database
- [ ] Prisma schema.prisma (full with tenant_id)
- [ ] npx prisma migrate dev
- [ ] Seed script

### 3. Backend Modules
- [ ] Auth (JWT, roles, tenant)
- [ ] Tenant/Academy CRUD
- [ ] Student CRUD + evolution score
- [ ] Financial + Mercado Pago
- [ ] Training/Attendance
- [ ] Dashboard aggregates

### 4. Frontend
- [ ] Auth pages
- [ ] Role-based dashboards
- [ ] CRUD pages (students, financial)
- [ ] Charts (Recharts)
- [ ] Payment links

### 5. Polish
- [ ] Notifications/Gamification
- [ ] Tests
- [ ] Commit, push, PR via gh

**Next: Create project directory and skeleton files.**

