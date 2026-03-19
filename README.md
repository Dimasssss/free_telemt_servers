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

# Server Metrics 2026-03-19 10:19:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 45036.2 (12h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 997552
telemt_connections_bad_total 87619
telemt_connections_current 1479
telemt_connections_me_current 1479
telemt_handshake_timeouts_total 36236
telemt_upstream_connect_attempt_total 8523
telemt_upstream_connect_success_total 8375
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 8523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 7285
telemt_me_reconnect_success_total 6125
telemt_me_reader_eof_total 6488
telemt_me_idle_close_by_peer_total 6487
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 339743
telemt_me_route_drop_channel_closed_total 151
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 766234
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4558
telemt_desync_full_logged_total 1394
telemt_desync_suppressed_total 3164
telemt_desync_frames_bucket_total{bucket="1_2"} 1521
telemt_desync_frames_bucket_total{bucket="3_10"} 1657
telemt_desync_frames_bucket_total{bucket="gt_10"} 1380
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6237
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 6105
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 760594
telemt_user_connections_current{user="hello"} 1479
telemt_user_octets_from_client{user="hello"} 11875526960 (11.06 GB)
telemt_user_octets_to_client{user="hello"} 242398939916 (225.75 GB)
telemt_user_unique_ips_current{user="hello"} 525
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 45041.1 (12h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2470318
telemt_connections_bad_total 155796
telemt_connections_current 4274
telemt_connections_me_current 4274
telemt_handshake_timeouts_total 54132
telemt_upstream_connect_attempt_total 8535
telemt_upstream_connect_success_total 8378
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 8535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 8458
telemt_me_reconnect_success_total 6105
telemt_me_reader_eof_total 6491
telemt_me_idle_close_by_peer_total 6491
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 1120120
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2043478
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9372
telemt_desync_full_logged_total 3107
telemt_desync_suppressed_total 6265
telemt_desync_frames_bucket_total{bucket="1_2"} 1725
telemt_desync_frames_bucket_total{bucket="3_10"} 3673
telemt_desync_frames_bucket_total{bucket="gt_10"} 3974
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6289
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 6083
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 2043161
telemt_user_connections_current{user="hello"} 4274
telemt_user_octets_from_client{user="hello"} 32013416264 (29.81 GB)
telemt_user_octets_to_client{user="hello"} 737352682288 (686.71 GB)
telemt_user_unique_ips_current{user="hello"} 1438
telemt_user_unique_ips_recent_window{user="hello"} 618
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 45038.5 (12h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2137061
telemt_connections_bad_total 253183
telemt_connections_current 2878
telemt_connections_me_current 2878
telemt_handshake_timeouts_total 47770
telemt_upstream_connect_attempt_total 8027
telemt_upstream_connect_success_total 8027
telemt_upstream_connect_attempts_per_request{bucket="1"} 8027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 5787
telemt_me_reconnect_success_total 5751
telemt_me_reader_eof_total 6082
telemt_me_idle_close_by_peer_total 6082
telemt_me_route_drop_no_conn_total 1316831
telemt_me_route_drop_channel_closed_total 65
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1675561
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7186
telemt_desync_full_logged_total 2302
telemt_desync_suppressed_total 4884
telemt_desync_frames_bucket_total{bucket="1_2"} 1597
telemt_desync_frames_bucket_total{bucket="3_10"} 2655
telemt_desync_frames_bucket_total{bucket="gt_10"} 2934
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 5852
telemt_me_writer_restored_same_endpoint_total 5735
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 1673945
telemt_user_connections_current{user="hello"} 2878
telemt_user_octets_from_client{user="hello"} 24231578608 (22.57 GB)
telemt_user_octets_to_client{user="hello"} 727459785060 (677.50 GB)
telemt_user_unique_ips_current{user="hello"} 1014
telemt_user_unique_ips_recent_window{user="hello"} 444
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 45091.2 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2113566
telemt_connections_bad_total 117819
telemt_connections_current 3080
telemt_connections_me_current 3080
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 55048
telemt_upstream_connect_attempt_total 16321
telemt_upstream_connect_success_total 16171
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 16321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4595
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 9031
telemt_me_reconnect_success_total 5715
telemt_me_reader_eof_total 6076
telemt_me_idle_close_by_peer_total 6075
telemt_me_route_drop_no_conn_total 1079311
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1599269
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5833
telemt_desync_full_logged_total 1983
telemt_desync_suppressed_total 3850
telemt_desync_frames_bucket_total{bucket="1_2"} 1214
telemt_desync_frames_bucket_total{bucket="3_10"} 2274
telemt_desync_frames_bucket_total{bucket="gt_10"} 2345
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6133
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 5691
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 418
telemt_user_connections_total{user="hello"} 1605497
telemt_user_connections_current{user="hello"} 3080
telemt_user_octets_from_client{user="hello"} 18565548268 (17.29 GB)
telemt_user_octets_to_client{user="hello"} 463690393778 (431.85 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1005
telemt_user_unique_ips_recent_window{user="hello"} 448
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 45034.5 (12h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2508740
telemt_connections_bad_total 570538
telemt_connections_current 3519
telemt_connections_me_current 3519
telemt_handshake_timeouts_total 50990
telemt_upstream_connect_attempt_total 7903
telemt_upstream_connect_success_total 7849
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 7903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3825
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 6794
telemt_me_reconnect_success_total 5596
telemt_me_reader_eof_total 5946
telemt_me_idle_close_by_peer_total 5946
telemt_me_route_drop_no_conn_total 933247
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1647301
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7398
telemt_desync_full_logged_total 2303
telemt_desync_suppressed_total 5095
telemt_desync_frames_bucket_total{bucket="1_2"} 1491
telemt_desync_frames_bucket_total{bucket="3_10"} 3199
telemt_desync_frames_bucket_total{bucket="gt_10"} 2708
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 5715
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5572
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 1646410
telemt_user_connections_current{user="hello"} 3519
telemt_user_octets_from_client{user="hello"} 29190132456 (27.19 GB)
telemt_user_octets_to_client{user="hello"} 690737031032 (643.30 GB)
telemt_user_unique_ips_current{user="hello"} 1193
telemt_user_unique_ips_recent_window{user="hello"} 505
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 45046.5 (12h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 442383
telemt_connections_bad_total 18281
telemt_connections_current 884
telemt_connections_me_current 884
telemt_handshake_timeouts_total 3468
telemt_upstream_connect_attempt_total 11277
telemt_upstream_connect_success_total 10992
telemt_upstream_connect_fail_total 285
telemt_upstream_connect_attempts_per_request{bucket="1"} 11277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 285
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 14121
telemt_me_reconnect_success_total 8731
telemt_me_reader_eof_total 9267
telemt_me_idle_close_by_peer_total 9267
telemt_me_route_drop_no_conn_total 225648
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 398388
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 742
telemt_desync_full_logged_total 255
telemt_desync_suppressed_total 487
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 285
telemt_desync_frames_bucket_total{bucket="gt_10"} 283
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 8974
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8701
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 398353
telemt_user_connections_current{user="hello"} 884
telemt_user_octets_from_client{user="hello"} 6291607088 (5.86 GB)
telemt_user_octets_to_client{user="hello"} 154425817048 (143.82 GB)
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 45037.2 (12h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1682339
telemt_connections_bad_total 136137
telemt_connections_current 3297
telemt_connections_me_current 3297
telemt_handshake_timeouts_total 68694
telemt_upstream_connect_attempt_total 9074
telemt_upstream_connect_success_total 9073
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8154
telemt_me_reconnect_success_total 6800
telemt_me_reader_eof_total 7202
telemt_me_idle_close_by_peer_total 7201
telemt_me_route_drop_no_conn_total 666337
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1403836
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7931
telemt_desync_full_logged_total 2576
telemt_desync_suppressed_total 5355
telemt_desync_frames_bucket_total{bucket="1_2"} 1485
telemt_desync_frames_bucket_total{bucket="3_10"} 2979
telemt_desync_frames_bucket_total{bucket="gt_10"} 3467
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 6926
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6785
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 1402646
telemt_user_connections_current{user="hello"} 3297
telemt_user_octets_from_client{user="hello"} 19237740024 (17.92 GB)
telemt_user_octets_to_client{user="hello"} 675444884000 (629.06 GB)
telemt_user_unique_ips_current{user="hello"} 1040
telemt_user_unique_ips_recent_window{user="hello"} 455
```