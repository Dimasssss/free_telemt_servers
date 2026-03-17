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

# Server Metrics 2026-03-17 14:03:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 69500.3 (19h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 715880
telemt_connections_bad_total 5693
telemt_handshake_timeouts_total 20695
telemt_upstream_connect_attempt_total 16993
telemt_upstream_connect_success_total 16539
telemt_upstream_connect_fail_total 454
telemt_upstream_connect_attempts_per_request{bucket="1"} 16993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 454
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 18943
telemt_me_reconnect_success_total 10778
telemt_me_reader_eof_total 11587
telemt_me_idle_close_by_peer_total 11586
telemt_me_route_drop_no_conn_total 268240
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 650038
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4595
telemt_desync_full_logged_total 1290
telemt_desync_suppressed_total 3305
telemt_desync_frames_bucket_total{bucket="1_2"} 1288
telemt_desync_frames_bucket_total{bucket="3_10"} 1885
telemt_desync_frames_bucket_total{bucket="gt_10"} 1422
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11185
telemt_me_refill_failed_total 250
telemt_me_writer_restored_same_endpoint_total 10756
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 407
telemt_user_connections_total{user="hello"} 651921
telemt_user_connections_current{user="hello"} 963
telemt_user_octets_from_client{user="hello"} 10666476927 (9.93 GB)
telemt_user_octets_to_client{user="hello"} 222472544871 (207.19 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 69752.3 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 446165
telemt_connections_bad_total 27689
telemt_handshake_timeouts_total 22349
telemt_upstream_connect_attempt_total 33427
telemt_upstream_connect_success_total 33053
telemt_upstream_connect_fail_total 372
telemt_upstream_connect_attempts_per_request{bucket="1"} 33425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9946
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 372
telemt_me_keepalive_timeout_total 314
telemt_me_reconnect_attempts_total 31741
telemt_me_reconnect_success_total 13340
telemt_me_reader_eof_total 14479
telemt_me_idle_close_by_peer_total 14479
telemt_me_route_drop_no_conn_total 186904
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357854
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1427
telemt_desync_full_logged_total 450
telemt_desync_suppressed_total 977
telemt_desync_frames_bucket_total{bucket="1_2"} 318
telemt_desync_frames_bucket_total{bucket="3_10"} 623
telemt_desync_frames_bucket_total{bucket="gt_10"} 486
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14078
telemt_me_refill_failed_total 571
telemt_me_writer_restored_same_endpoint_total 13324
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 738
telemt_user_connections_total{user="hello"} 373974
telemt_user_connections_current{user="hello"} 666
telemt_user_octets_from_client{user="hello"} 4048016666 (3.77 GB)
telemt_user_octets_to_client{user="hello"} 120443567552 (112.17 GB)
telemt_user_msgs_from_client{user="hello"} 247348
telemt_user_msgs_to_client{user="hello"} 748336
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 69527.5 (19h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234596
telemt_connections_bad_total 7807
telemt_handshake_timeouts_total 16872
telemt_upstream_connect_attempt_total 18421
telemt_upstream_connect_success_total 18327
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 18421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10093
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 21499
telemt_me_reconnect_success_total 14786
telemt_me_reader_eof_total 15871
telemt_me_idle_close_by_peer_total 15871
telemt_me_route_drop_no_conn_total 90985
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197591
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 747
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 535
telemt_desync_frames_bucket_total{bucket="1_2"} 275
telemt_desync_frames_bucket_total{bucket="3_10"} 331
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 15203
telemt_me_refill_failed_total 207
telemt_me_writer_restored_same_endpoint_total 14775
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 417
telemt_user_connections_total{user="hello"} 197464
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 15380187668 (14.32 GB)
telemt_user_octets_to_client{user="hello"} 52927723776 (49.29 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 69587.0 (19h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 538086
telemt_connections_bad_total 8084
telemt_handshake_timeouts_total 12974
telemt_upstream_connect_attempt_total 16465
telemt_upstream_connect_success_total 16315
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 16465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8035
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 21136
telemt_me_reconnect_success_total 11765
telemt_me_reader_eof_total 12718
telemt_me_idle_close_by_peer_total 12718
telemt_me_route_drop_no_conn_total 169618
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 458941
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1598
telemt_desync_full_logged_total 551
telemt_desync_suppressed_total 1047
telemt_desync_frames_bucket_total{bucket="1_2"} 395
telemt_desync_frames_bucket_total{bucket="3_10"} 719
telemt_desync_frames_bucket_total{bucket="gt_10"} 484
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12263
telemt_me_refill_failed_total 288
telemt_me_writer_restored_same_endpoint_total 11756
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 498
telemt_user_connections_total{user="hello"} 459808
telemt_user_connections_current{user="hello"} 803
telemt_user_octets_from_client{user="hello"} 5739486926 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 153546263379 (143.00 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 69558.9 (19h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266243
telemt_connections_bad_total 56561
telemt_handshake_timeouts_total 3337
telemt_upstream_connect_attempt_total 20344
telemt_upstream_connect_success_total 19893
telemt_upstream_connect_fail_total 451
telemt_upstream_connect_attempts_per_request{bucket="1"} 20344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10624
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 274
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 451
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 36003
telemt_me_reconnect_success_total 15984
telemt_me_reader_eof_total 17194
telemt_me_idle_close_by_peer_total 17192
telemt_me_route_drop_no_conn_total 75061
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195598
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1095
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 866
telemt_desync_frames_bucket_total{bucket="1_2"} 546
telemt_desync_frames_bucket_total{bucket="3_10"} 420
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 16878
telemt_me_refill_failed_total 621
telemt_me_writer_restored_same_endpoint_total 15976
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 894
telemt_user_connections_total{user="hello"} 196053
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 2547496219 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 72369224735 (67.40 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 69721.3 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 635335
telemt_connections_bad_total 53490
telemt_handshake_timeouts_total 6225
telemt_upstream_connect_attempt_total 14051
telemt_upstream_connect_success_total 13976
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 14051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7058
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 19509
telemt_me_reconnect_success_total 10476
telemt_me_reader_eof_total 11399
telemt_me_idle_close_by_peer_total 11399
telemt_me_route_drop_no_conn_total 441193
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 638450
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 845
telemt_desync_full_logged_total 313
telemt_desync_suppressed_total 532
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 328
telemt_desync_frames_bucket_total{bucket="gt_10"} 307
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10919
telemt_me_refill_failed_total 280
telemt_me_writer_restored_same_endpoint_total 10462
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 443
telemt_user_connections_total{user="hello"} 542934
telemt_user_connections_current{user="hello"} 910
telemt_user_octets_from_client{user="hello"} 8232927012 (7.67 GB)
telemt_user_octets_to_client{user="hello"} 251287703376 (234.03 GB)
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 17487.0 (4h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14064
telemt_connections_bad_total 62
telemt_handshake_timeouts_total 126
telemt_upstream_connect_attempt_total 9915
telemt_upstream_connect_success_total 9834
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 9915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 17856
telemt_me_reconnect_success_total 8776
telemt_me_reader_eof_total 9258
telemt_me_idle_close_by_peer_total 9258
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 4820
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13514
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 9144
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 8761
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 13615
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 374534137 (357.18 MB)
telemt_user_octets_to_client{user="hello"} 22352927146 (20.82 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 9
```