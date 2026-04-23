# See https://help.github.com/articles/ignoring-files/ for more about ignoring files.

# dependencies
/node_modules
/.pnp
.pnp.*
.yarn/*
!.yarn/patches
!.yarn/plugins
!.yarn/releases
!.yarn/versions

# testing
/coverage

# next.js
/.next/
/out/

# production
/build

# misc
.DS_Store
*.pem

# debug
npm-debug.log*
yarn-debug.log*
yarn-error.log*
.pnpm-debug.log*

# env files (can opt-in for committing if needed)
.env*

# vercel
.vercel

# typescript
*.tsbuildinfo
next-env.d.ts,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,




http://localhost:3000/dashboard/cms


DATABASE_URL=postgresql://neondb_owner:npg_yPKNwSz0a9vL@ep-solitary-moon-ak1wm1x5-pooler.c-3.us-west-2.aws.neon.tech/neondb?sslmode=require&channel_binding=require&pgbouncer=true&connection_limit=1

DIRECT_URL=postgresql://neondb_owner:npg_yPKNwSz0a9vL@ep-solitary-moon-ak1wm1x5.c-3.us-west-2.aws.neon.tech/neondb?sslmode=require&channel_binding=require

CMS_SUPERADMIN_EMAIL=brightg@yascon.org
CMS_SUPERADMIN_PASSWORD=
CMS_SUPERADMIN_NAME=

For cloudinary
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=dqwpoqhrg
CLOUDINARY_API_KEY=269884449624367
CLOUDINARY_API_SECRET=XfgvHICCQVFuLLigLyLSzpxP_CA
CLOUDINARY_URL=cloudinary://269884449624367:XfgvHICCQVFuLLigLyLSzpxP_CA@dqwpoqhrg
NEXT_PUBLIC_CLOUDINARY_SECURE_DISTRIBUTION=<Your Secure Distribution / CNAME>
NEXT_PUBLIC_CLOUDINARY_PRIVATE_CDN=<true|false>






