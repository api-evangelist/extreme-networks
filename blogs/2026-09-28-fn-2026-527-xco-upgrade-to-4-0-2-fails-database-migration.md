---
title: "FN-2026-527 - XCO UPGRADE TO 4.0.2 FAILS DATABASE MIGRATION ERROR"
url: "https://community.extremenetworks.com/t5/slx-announcements/fn-2026-527-xco-upgrade-to-4-0-2-fails-database-migration-error/ba-p/122676"
date: "2026-09-28"
author: "Dana_Breckbill"
feed_url: "https://community.extremenetworks.com/zxxfm75553/rss/Community?interaction.style=blog&feeds.replies=true"
---
Summary: When duplicate SNMP communities are configured prior to an XCO upgrade to 4.0.2, upgrade fails at the inventory database migration step ( dcapp_asset ). This issue can also happen due to duplicate “ MigrationComplete ” entries which can be seen on deployments that have undergone multiple upgrades.
