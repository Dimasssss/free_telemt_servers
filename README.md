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

# Server Metrics 2026-03-14 20:07:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 24691.6 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129271
telemt_connections_bad_total 16017
telemt_handshake_timeouts_total 1265
telemt_upstream_connect_attempt_total 5604
telemt_upstream_connect_success_total 5602
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 5604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2863
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 188
telemt_me_reconnect_attempts_total 4356
telemt_me_reconnect_success_total 4321
telemt_me_reader_eof_total 4586
telemt_me_idle_close_by_peer_total 4586
telemt_me_route_drop_no_conn_total 46199
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106251
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 453
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4393
telemt_me_writer_restored_same_endpoint_total 4303
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 106174
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 2274223392 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 57401379600 (53.46 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 24690.7 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52479
telemt_connections_bad_total 683
telemt_handshake_timeouts_total 953
telemt_upstream_connect_attempt_total 6407
telemt_upstream_connect_success_total 6365
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 6407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 7660
telemt_me_reconnect_success_total 5084
telemt_me_reader_eof_total 5411
telemt_me_idle_close_by_peer_total 5411
telemt_me_route_drop_no_conn_total 27629
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48863
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 5234
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 5079
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 48852
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 1295349884 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 20549387044 (19.14 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 24694.9 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58802
telemt_connections_bad_total 386
telemt_handshake_timeouts_total 1868
telemt_upstream_connect_attempt_total 8324
telemt_upstream_connect_success_total 8238
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 8324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 104501
telemt_me_reconnect_success_total 6638
telemt_me_reader_eof_total 7091
telemt_me_idle_close_by_peer_total 7091
telemt_me_route_drop_no_conn_total 22548
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53448
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 6910
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 6596
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 53513
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 3400583137 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 39978575286 (37.23 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 24699.9 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75236
telemt_connections_bad_total 204
telemt_handshake_timeouts_total 569
telemt_upstream_connect_attempt_total 6131
telemt_upstream_connect_success_total 6093
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 6131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 179
telemt_me_reconnect_attempts_total 4672
telemt_me_reconnect_success_total 4647
telemt_me_reader_eof_total 4883
telemt_me_idle_close_by_peer_total 4883
telemt_me_route_drop_no_conn_total 32565
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71159
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 587
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 246
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4699
telemt_me_writer_restored_same_endpoint_total 4645
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 71207
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 1057369740 (1008.39 MB)
telemt_user_octets_to_client{user="hello"} 23144740810 (21.56 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 24692.9 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54941
telemt_connections_bad_total 4778
telemt_handshake_timeouts_total 3238
telemt_upstream_connect_attempt_total 5779
telemt_upstream_connect_success_total 5714
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 5779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 10962
telemt_me_reconnect_success_total 4428
telemt_me_reader_eof_total 4832
telemt_me_idle_close_by_peer_total 4832
telemt_me_route_drop_no_conn_total 18413
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44347
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 252
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4675
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 4424
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 44334
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 1351095028 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 25661970948 (23.90 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 24692.4 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190923
telemt_connections_bad_total 7280
telemt_handshake_timeouts_total 2624
telemt_upstream_connect_attempt_total 4841
telemt_upstream_connect_success_total 4753
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 4841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2419
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 248
telemt_me_reconnect_attempts_total 8478
telemt_me_reconnect_success_total 3473
telemt_me_reader_eof_total 3771
telemt_me_idle_close_by_peer_total 3771
telemt_me_route_drop_no_conn_total 107270
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175401
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
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3669
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3469
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 171890
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 3690685236 (3.44 GB)
telemt_user_octets_to_client{user="hello"} 84847923780 (79.02 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 49
```