公网用户
   │
   ▼
[ Cloudflare / 域名DNS ] ── 可选，但加上很加分
   │
   ▼
[ WAF ] ── 华为云WAF，防SQL注入/XSS，说明你有安全意识
   │
   ▼
[ ELB ] ── 转发到后端ECS集群
   │
   ├── ECS 01（Nginx + PHP + WordPress）── 可用区A
   ├── ECS 02（Nginx + PHP + WordPress）── 可用区B
   │
   ▼
[ RDS MySQL 主备 ] ── 跨可用区部署
   │
   ▼
[ OBS ] ── 静态资源 + 数据库备份 + 日志归档
