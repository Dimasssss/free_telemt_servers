# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-18 23:45:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 7001.0 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81729
telemt_connections_bad_total 8327
telemt_connections_current 609
telemt_connections_me_current 609
telemt_handshake_timeouts_total 845
telemt_upstream_connect_attempt_total 1285
telemt_upstream_connect_success_total 1266
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 680
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 903
telemt_me_reconnect_success_total 901
telemt_me_reader_eof_total 923
telemt_me_idle_close_by_peer_total 923
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 26810
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69866
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 370
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 248
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 900
telemt_me_writer_restored_same_endpoint_total 890
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 67110
telemt_user_connections_current{user="hello"} 609
telemt_user_octets_from_client{user="hello"} 678202052 (646.78 MB)
telemt_user_octets_to_client{user="hello"} 29179308220 (27.18 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 7004.5 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184871
telemt_connections_bad_total 15171
telemt_connections_current 1522
telemt_connections_me_current 1522
telemt_handshake_timeouts_total 1556
telemt_upstream_connect_attempt_total 1338
telemt_upstream_connect_success_total 1305
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 1338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 935
telemt_me_reconnect_success_total 934
telemt_me_reader_eof_total 969
telemt_me_idle_close_by_peer_total 969
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 57796
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158181
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 649
telemt_desync_full_logged_total 219
telemt_desync_suppressed_total 430
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 222
telemt_desync_frames_bucket_total{bucket="gt_10"} 294
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 950
telemt_me_writer_restored_same_endpoint_total 923
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 158260
telemt_user_connections_current{user="hello"} 1522
telemt_user_octets_from_client{user="hello"} 10279829748 (9.57 GB)
telemt_user_octets_to_client{user="hello"} 61209999460 (57.01 GB)
telemt_user_unique_ips_current{user="hello"} 607
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 7001.7 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144219
telemt_connections_bad_total 21639
telemt_connections_current 1081
telemt_connections_me_current 1081
telemt_handshake_timeouts_total 4256
telemt_upstream_connect_attempt_total 1344
telemt_upstream_connect_success_total 1344
telemt_upstream_connect_attempts_per_request{bucket="1"} 1344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 664
telemt_me_reconnect_attempts_total 975
telemt_me_reconnect_success_total 973
telemt_me_reader_eof_total 1004
telemt_me_idle_close_by_peer_total 1004
telemt_me_route_drop_no_conn_total 49517
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114478
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 484
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 294
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 201
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 985
telemt_me_writer_restored_same_endpoint_total 957
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 114479
telemt_user_connections_current{user="hello"} 1081
telemt_user_octets_from_client{user="hello"} 1468608920 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 70809498356 (65.95 GB)
telemt_user_unique_ips_current{user="hello"} 507
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 7055.3 (1h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155560
telemt_connections_bad_total 23852
telemt_connections_current 995
telemt_connections_me_current 995
telemt_handshake_timeouts_total 3174
telemt_upstream_connect_attempt_total 1281
telemt_upstream_connect_success_total 1281
telemt_upstream_connect_attempts_per_request{bucket="1"} 1281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 915
telemt_me_reconnect_success_total 912
telemt_me_reader_eof_total 938
telemt_me_idle_close_by_peer_total 938
telemt_me_route_drop_no_conn_total 61502
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119796
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 282
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 175
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 925
telemt_me_writer_restored_same_endpoint_total 888
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 119724
telemt_user_connections_current{user="hello"} 995
telemt_user_octets_from_client{user="hello"} 1207522956 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 45200166928 (42.10 GB)
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 6998.5 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159079
telemt_connections_bad_total 7107
telemt_connections_current 1243
telemt_connections_me_current 1243
telemt_handshake_timeouts_total 5212
telemt_upstream_connect_attempt_total 1276
telemt_upstream_connect_success_total 1269
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 635
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 899
telemt_me_reconnect_success_total 895
telemt_me_reader_eof_total 917
telemt_me_idle_close_by_peer_total 917
telemt_me_route_drop_no_conn_total 49963
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125154
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 531
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 315
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 897
telemt_me_writer_restored_same_endpoint_total 871
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 125099
telemt_user_connections_current{user="hello"} 1243
telemt_user_octets_from_client{user="hello"} 1593796212 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 79022994228 (73.60 GB)
telemt_user_unique_ips_current{user="hello"} 530
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 7010.4 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37202
telemt_connections_bad_total 6769
telemt_connections_current 353
telemt_connections_me_current 353
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 2183
telemt_upstream_connect_success_total 2122
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 2183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1051
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_reconnect_attempts_total 3582
telemt_me_reconnect_success_total 1756
telemt_me_reader_eof_total 1813
telemt_me_idle_close_by_peer_total 1813
telemt_me_route_drop_no_conn_total 12709
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29524
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1789
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 1726
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 29525
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 348613332 (332.46 MB)
telemt_user_octets_to_client{user="hello"} 23169405980 (21.58 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 7000.8 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117536
telemt_connections_bad_total 15205
telemt_connections_current 1050
telemt_connections_me_current 1050
telemt_handshake_timeouts_total 4075
telemt_upstream_connect_attempt_total 1339
telemt_upstream_connect_success_total 1339
telemt_upstream_connect_attempts_per_request{bucket="1"} 1339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 969
telemt_me_reconnect_success_total 966
telemt_me_reader_eof_total 998
telemt_me_idle_close_by_peer_total 998
telemt_me_route_drop_no_conn_total 35540
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95948
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 675
telemt_desync_full_logged_total 258
telemt_desync_suppressed_total 417
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 282
telemt_desync_frames_bucket_total{bucket="gt_10"} 277
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 978
telemt_me_writer_restored_same_endpoint_total 951
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 95973
telemt_user_connections_current{user="hello"} 1050
telemt_user_octets_from_client{user="hello"} 976338696 (931.11 MB)
telemt_user_octets_to_client{user="hello"} 52034676560 (48.46 GB)
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 103
```