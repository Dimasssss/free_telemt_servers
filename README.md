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

# Server Metrics 2026-03-12 23:42:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 58156.2 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251937
telemt_connections_bad_total 2736
telemt_handshake_timeouts_total 5260
telemt_upstream_connect_attempt_total 14647
telemt_upstream_connect_success_total 14584
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 14647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8098
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1486
telemt_me_reconnect_attempts_total 15113
telemt_me_reconnect_success_total 11642
telemt_me_reader_eof_total 12407
telemt_me_idle_close_by_peer_total 12406
telemt_me_route_drop_no_conn_total 78316
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208197
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 696
telemt_desync_full_logged_total 257
telemt_desync_suppressed_total 439
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11881
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 11626
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 207963
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 3844573512 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 106384842404 (99.08 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 58049.4 (16h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115126
telemt_connections_bad_total 635
telemt_handshake_timeouts_total 905
telemt_upstream_connect_attempt_total 33476
telemt_upstream_connect_success_total 33095
telemt_upstream_connect_fail_total 381
telemt_upstream_connect_attempts_per_request{bucket="1"} 33476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 500
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 381
telemt_me_keepalive_timeout_total 413
telemt_me_reconnect_attempts_total 55538
telemt_me_reconnect_success_total 13666
telemt_me_reader_eof_total 15331
telemt_me_idle_close_by_peer_total 15331
telemt_me_route_drop_no_conn_total 41760
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92825
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 15072
telemt_me_refill_failed_total 1307
telemt_me_writer_restored_same_endpoint_total 13651
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1406
telemt_user_connections_total{user="hello"} 109327
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 1207197488 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 34041600495 (31.70 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 58012.9 (16h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140668
telemt_connections_bad_total 1661
telemt_handshake_timeouts_total 2240
telemt_upstream_connect_attempt_total 15946
telemt_upstream_connect_success_total 15945
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8443
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 339
telemt_me_reconnect_attempts_total 14126
telemt_me_reconnect_success_total 12977
telemt_me_reader_eof_total 13857
telemt_me_idle_close_by_peer_total 13857
telemt_me_route_drop_no_conn_total 53033
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131484
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 13139
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 12957
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 131450
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 2603992048 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 60662088556 (56.50 GB)
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 57988.5 (16h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204024
telemt_connections_bad_total 13276
telemt_handshake_timeouts_total 1381
telemt_upstream_connect_attempt_total 27466
telemt_upstream_connect_success_total 17752
telemt_upstream_connect_fail_total 9714
telemt_upstream_connect_attempts_per_request{bucket="1"} 27466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8248
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9714
telemt_me_keepalive_timeout_total 2503
telemt_me_reconnect_attempts_total 44207
telemt_me_reconnect_success_total 11959
telemt_me_reader_eof_total 13413
telemt_me_idle_close_by_peer_total 13406
telemt_me_route_drop_no_conn_total 72214
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168001
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13146
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 11949
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1187
telemt_user_connections_total{user="hello"} 170755
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 2988682390 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 69624789741 (64.84 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 8160.1 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7304
telemt_connections_bad_total 1515
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 2598
telemt_upstream_connect_success_total 2570
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 2138
telemt_me_reconnect_success_total 2135
telemt_me_reader_eof_total 2237
telemt_me_idle_close_by_peer_total 2237
telemt_me_route_drop_no_conn_total 2074
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5531
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2147
telemt_me_writer_restored_same_endpoint_total 2119
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 5531
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 18299596 (17.45 MB)
telemt_user_octets_to_client{user="hello"} 1821711780 (1.70 GB)
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 57944.9 (16h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336253
telemt_connections_bad_total 5148
telemt_handshake_timeouts_total 2534
telemt_upstream_connect_attempt_total 12173
telemt_upstream_connect_success_total 12105
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 12173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6395
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 514
telemt_me_reconnect_attempts_total 12809
telemt_me_reconnect_success_total 9195
telemt_me_reader_eof_total 9835
telemt_me_idle_close_by_peer_total 9834
telemt_me_route_drop_no_conn_total 150682
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330502
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9419
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 9188
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 318805
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 5520642208 (5.14 GB)
telemt_user_octets_to_client{user="hello"} 171697459024 (159.91 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 29
```