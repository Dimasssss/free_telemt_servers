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

# Server Metrics 2026-03-14 19:47:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 23466.3 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124767
telemt_connections_bad_total 15891
telemt_handshake_timeouts_total 1179
telemt_upstream_connect_attempt_total 5322
telemt_upstream_connect_success_total 5320
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4134
telemt_me_reconnect_success_total 4099
telemt_me_reader_eof_total 4342
telemt_me_idle_close_by_peer_total 4342
telemt_me_route_drop_no_conn_total 44313
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102199
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 421
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 267
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4167
telemt_me_writer_restored_same_endpoint_total 4081
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 102121
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 2088712176 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 52013821696 (48.44 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 23464.5 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50527
telemt_connections_bad_total 668
telemt_handshake_timeouts_total 934
telemt_upstream_connect_attempt_total 6095
telemt_upstream_connect_success_total 6054
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 6095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 7413
telemt_me_reconnect_success_total 4838
telemt_me_reader_eof_total 5142
telemt_me_idle_close_by_peer_total 5142
telemt_me_route_drop_no_conn_total 26928
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47076
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4984
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 4833
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 47068
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 1277927488 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 19746766332 (18.39 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 23468.8 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55917
telemt_connections_bad_total 386
telemt_handshake_timeouts_total 1859
telemt_upstream_connect_attempt_total 8001
telemt_upstream_connect_success_total 7918
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 8001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4170
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 219
telemt_me_reconnect_attempts_total 104248
telemt_me_reconnect_success_total 6385
telemt_me_reader_eof_total 6806
telemt_me_idle_close_by_peer_total 6806
telemt_me_route_drop_no_conn_total 21617
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50669
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 6653
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 6343
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 50737
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 3293418329 (3.07 GB)
telemt_user_octets_to_client{user="hello"} 37907993994 (35.30 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 23473.7 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71337
telemt_connections_bad_total 181
telemt_handshake_timeouts_total 568
telemt_upstream_connect_attempt_total 5698
telemt_upstream_connect_success_total 5663
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 5698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3060
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 4471
telemt_me_reconnect_success_total 4447
telemt_me_reader_eof_total 4670
telemt_me_idle_close_by_peer_total 4670
telemt_me_route_drop_no_conn_total 31414
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67542
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 567
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 424
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 232
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4496
telemt_me_writer_restored_same_endpoint_total 4445
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 67418
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 964924784 (920.22 MB)
telemt_user_octets_to_client{user="hello"} 21714302624 (20.22 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 23466.9 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52875
telemt_connections_bad_total 4517
telemt_handshake_timeouts_total 3220
telemt_upstream_connect_attempt_total 5421
telemt_upstream_connect_success_total 5360
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 5420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 10672
telemt_me_reconnect_success_total 4140
telemt_me_reader_eof_total 4521
telemt_me_idle_close_by_peer_total 4521
telemt_me_route_drop_no_conn_total 17941
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42655
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 251
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4386
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 4136
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 42643
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 1322530296 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 18225668648 (16.97 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 23466.6 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183658
telemt_connections_bad_total 7224
telemt_handshake_timeouts_total 2619
telemt_upstream_connect_attempt_total 4577
telemt_upstream_connect_success_total 4496
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 4577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2282
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 8286
telemt_me_reconnect_success_total 3285
telemt_me_reader_eof_total 3567
telemt_me_idle_close_by_peer_total 3567
telemt_me_route_drop_no_conn_total 104010
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168462
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3477
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3281
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 164951
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 3521693432 (3.28 GB)
telemt_user_octets_to_client{user="hello"} 81797022552 (76.18 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 58
```