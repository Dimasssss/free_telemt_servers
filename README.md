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

# Server Metrics 2026-03-13 16:42:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 119324.9 (33h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 498439
telemt_connections_bad_total 4766
telemt_handshake_timeouts_total 9668
telemt_upstream_connect_attempt_total 29679
telemt_upstream_connect_success_total 29535
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 29679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2602
telemt_me_reconnect_attempts_total 27109
telemt_me_reconnect_success_total 23567
telemt_me_reader_eof_total 25180
telemt_me_idle_close_by_peer_total 25179
telemt_me_route_drop_no_conn_total 162879
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 436801
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1400
telemt_desync_full_logged_total 491
telemt_desync_suppressed_total 909
telemt_desync_frames_bucket_total{bucket="1_2"} 306
telemt_desync_frames_bucket_total{bucket="3_10"} 504
telemt_desync_frames_bucket_total{bucket="gt_10"} 590
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 23929
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 23551
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 436372
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 7798254656 (7.26 GB)
telemt_user_octets_to_client{user="hello"} 202447130264 (188.54 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 119218.1 (33h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242809
telemt_connections_bad_total 1885
telemt_handshake_timeouts_total 1764
telemt_upstream_connect_attempt_total 98482
telemt_upstream_connect_success_total 97670
telemt_upstream_connect_fail_total 812
telemt_upstream_connect_attempts_per_request{bucket="1"} 98482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1295
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 812
telemt_me_keepalive_timeout_total 1468
telemt_me_reconnect_attempts_total 120448
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29737
telemt_me_idle_close_by_peer_total 29737
telemt_me_route_drop_no_conn_total 81921
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164328
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29207
telemt_me_refill_failed_total 2946
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3174
telemt_user_connections_total{user="hello"} 229789
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 2417923032 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 71437066468 (66.53 GB)
telemt_user_msgs_from_client{user="hello"} 1030067
telemt_user_msgs_to_client{user="hello"} 6088290
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 119181.7 (33h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290083
telemt_connections_bad_total 2448
telemt_handshake_timeouts_total 14740
telemt_upstream_connect_attempt_total 31913
telemt_upstream_connect_success_total 31909
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 31913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17056
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2473
telemt_me_reconnect_attempts_total 27125
telemt_me_reconnect_success_total 25901
telemt_me_reader_eof_total 27760
telemt_me_idle_close_by_peer_total 27760
telemt_me_route_drop_no_conn_total 104179
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262631
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 26190
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 25881
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 262542
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 10098122572 (9.40 GB)
telemt_user_octets_to_client{user="hello"} 110061832300 (102.50 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 119157.1 (33h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393580
telemt_connections_bad_total 15069
telemt_handshake_timeouts_total 3830
telemt_upstream_connect_attempt_total 48056
telemt_upstream_connect_success_total 37854
telemt_upstream_connect_fail_total 10202
telemt_upstream_connect_attempts_per_request{bucket="1"} 48056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16623
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10202
telemt_me_keepalive_timeout_total 4188
telemt_me_reconnect_attempts_total 109857
telemt_me_reconnect_success_total 24311
telemt_me_reader_eof_total 27692
telemt_me_idle_close_by_peer_total 27685
telemt_me_route_drop_no_conn_total 139438
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338018
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1350
telemt_desync_full_logged_total 402
telemt_desync_suppressed_total 948
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 27292
telemt_me_refill_failed_total 2668
telemt_me_writer_restored_same_endpoint_total 24301
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2981
telemt_user_connections_total{user="hello"} 345465
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 8111319674 (7.55 GB)
telemt_user_octets_to_client{user="hello"} 126681409851 (117.98 GB)
telemt_user_msgs_from_client{user="hello"} 286392
telemt_user_msgs_to_client{user="hello"} 339817
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 69328.6 (19h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110854
telemt_connections_bad_total 14424
telemt_handshake_timeouts_total 1367
telemt_upstream_connect_attempt_total 27715
telemt_upstream_connect_success_total 27468
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 27714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_timeout_total 1105
telemt_me_reconnect_attempts_total 30287
telemt_me_reconnect_success_total 19110
telemt_me_reader_eof_total 20472
telemt_me_idle_close_by_peer_total 20472
telemt_me_route_drop_no_conn_total 34131
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86615
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 19628
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 19092
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 518
telemt_user_connections_total{user="hello"} 91514
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 1041495481 (993.25 MB)
telemt_user_octets_to_client{user="hello"} 28493288131 (26.54 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 119114.2 (33h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 726321
telemt_connections_bad_total 24641
telemt_handshake_timeouts_total 24104
telemt_upstream_connect_attempt_total 24910
telemt_upstream_connect_success_total 24785
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 24910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13112
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 2635
telemt_me_reconnect_attempts_total 23488
telemt_me_reconnect_success_total 18855
telemt_me_reader_eof_total 20228
telemt_me_idle_close_by_peer_total 20225
telemt_me_route_drop_no_conn_total 342914
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 680951
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 667
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 19241
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18848
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 653840
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 11353055312 (10.57 GB)
telemt_user_octets_to_client{user="hello"} 332804429204 (309.95 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 63
```