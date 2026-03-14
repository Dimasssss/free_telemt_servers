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

# Server Metrics 2026-03-14 20:58:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 27754.5 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138782
telemt_connections_bad_total 16183
telemt_handshake_timeouts_total 1486
telemt_upstream_connect_attempt_total 6211
telemt_upstream_connect_success_total 6209
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 220
telemt_me_reconnect_attempts_total 4833
telemt_me_reconnect_success_total 4796
telemt_me_reader_eof_total 5085
telemt_me_idle_close_by_peer_total 5085
telemt_me_route_drop_no_conn_total 50372
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114858
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 529
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 339
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 193
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4877
telemt_me_writer_restored_same_endpoint_total 4778
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 114778
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 2464606696 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 68928640428 (64.19 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 27752.8 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57237
telemt_connections_bad_total 729
telemt_handshake_timeouts_total 991
telemt_upstream_connect_attempt_total 7213
telemt_upstream_connect_success_total 7168
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 7213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4092
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 133
telemt_me_reconnect_attempts_total 8333
telemt_me_reconnect_success_total 5754
telemt_me_reader_eof_total 6115
telemt_me_idle_close_by_peer_total 6115
telemt_me_route_drop_no_conn_total 29442
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53281
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 5911
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 5749
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 53269
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 1347651356 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 24053084632 (22.40 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 27757.1 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64092
telemt_connections_bad_total 393
telemt_handshake_timeouts_total 1893
telemt_upstream_connect_attempt_total 9065
telemt_upstream_connect_success_total 8974
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 9065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4764
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 254
telemt_me_reconnect_attempts_total 105107
telemt_me_reconnect_success_total 7243
telemt_me_reader_eof_total 7740
telemt_me_idle_close_by_peer_total 7740
telemt_me_route_drop_no_conn_total 24152
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58499
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 11
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
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 7523
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 7197
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 58565
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 3865608217 (3.60 GB)
telemt_user_octets_to_client{user="hello"} 42346731402 (39.44 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 27762.0 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81808
telemt_connections_bad_total 206
telemt_handshake_timeouts_total 606
telemt_upstream_connect_attempt_total 6814
telemt_upstream_connect_success_total 6773
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 6814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3582
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 192
telemt_me_reconnect_attempts_total 5223
telemt_me_reconnect_success_total 5196
telemt_me_reader_eof_total 5470
telemt_me_idle_close_by_peer_total 5470
telemt_me_route_drop_no_conn_total 35302
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77516
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 623
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 262
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5254
telemt_me_writer_restored_same_endpoint_total 5194
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 77562
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 1272245308 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 26633310598 (24.80 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 27755.0 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60028
telemt_connections_bad_total 5345
telemt_handshake_timeouts_total 3333
telemt_upstream_connect_attempt_total 6695
telemt_upstream_connect_success_total 6619
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 6695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3594
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 200
telemt_me_reconnect_attempts_total 11738
telemt_me_reconnect_success_total 5201
telemt_me_reader_eof_total 5627
telemt_me_idle_close_by_peer_total 5627
telemt_me_route_drop_no_conn_total 19745
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48486
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 262
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 5453
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 5197
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 48473
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 1383303160 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 29839700332 (27.79 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 27754.6 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205944
telemt_connections_bad_total 7312
telemt_handshake_timeouts_total 2662
telemt_upstream_connect_attempt_total 5419
telemt_upstream_connect_success_total 5320
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 5419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2728
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 252
telemt_me_reconnect_attempts_total 8914
telemt_me_reconnect_success_total 3906
telemt_me_reader_eof_total 4235
telemt_me_idle_close_by_peer_total 4235
telemt_me_route_drop_no_conn_total 115300
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189951
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4109
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3902
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 186437
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 4159357848 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 100023058096 (93.15 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 45
```