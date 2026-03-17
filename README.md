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

# Server Metrics 2026-03-17 22:44:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 100732.6 (27h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1216141
telemt_connections_bad_total 8800
telemt_handshake_timeouts_total 32221
telemt_upstream_connect_attempt_total 22711
telemt_upstream_connect_success_total 22217
telemt_upstream_connect_fail_total 494
telemt_upstream_connect_attempts_per_request{bucket="1"} 22711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 494
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32038
telemt_me_reconnect_success_total 14906
telemt_me_reader_eof_total 16195
telemt_me_idle_close_by_peer_total 16194
telemt_me_route_drop_no_conn_total 541135
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1116085
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7346
telemt_desync_full_logged_total 2133
telemt_desync_suppressed_total 5213
telemt_desync_frames_bucket_total{bucket="1_2"} 1965
telemt_desync_frames_bucket_total{bucket="3_10"} 2775
telemt_desync_frames_bucket_total{bucket="gt_10"} 2606
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 15660
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14884
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 754
telemt_user_connections_total{user="hello"} 1110310
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 20776609479 (19.35 GB)
telemt_user_octets_to_client{user="hello"} 399895006155 (372.43 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 100983.5 (28h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1285850
telemt_connections_bad_total 60429
telemt_handshake_timeouts_total 45040
telemt_upstream_connect_attempt_total 458233
telemt_upstream_connect_success_total 457330
telemt_upstream_connect_fail_total 903
telemt_upstream_connect_attempts_per_request{bucket="1"} 458233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30921
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 903
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58426
telemt_me_reconnect_success_total 15270
telemt_me_reader_eof_total 17285
telemt_me_idle_close_by_peer_total 17285
telemt_me_route_drop_no_conn_total 333937
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 678448
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3037
telemt_desync_full_logged_total 998
telemt_desync_suppressed_total 2039
telemt_desync_frames_bucket_total{bucket="1_2"} 580
telemt_desync_frames_bucket_total{bucket="3_10"} 1248
telemt_desync_frames_bucket_total{bucket="gt_10"} 1209
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 16805
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15254
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1535
telemt_user_connections_total{user="hello"} 1114880
telemt_user_connections_current{user="hello"} 803
telemt_user_octets_from_client{user="hello"} 15287367614 (14.24 GB)
telemt_user_octets_to_client{user="hello"} 380989398702 (354.82 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 100759.6 (27h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 746919
telemt_connections_bad_total 46341
telemt_handshake_timeouts_total 23516
telemt_upstream_connect_attempt_total 23815
telemt_upstream_connect_success_total 23676
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 23815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39291
telemt_me_reconnect_success_total 18611
telemt_me_reader_eof_total 20292
telemt_me_idle_close_by_peer_total 20285
telemt_me_route_drop_no_conn_total 308916
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 638290
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2097
telemt_desync_full_logged_total 667
telemt_desync_suppressed_total 1430
telemt_desync_frames_bucket_total{bucket="1_2"} 587
telemt_desync_frames_bucket_total{bucket="3_10"} 814
telemt_desync_frames_bucket_total{bucket="gt_10"} 696
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 19512
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18599
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 901
telemt_user_connections_total{user="hello"} 636551
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 31102426708 (28.97 GB)
telemt_user_octets_to_client{user="hello"} 277405436328 (258.35 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 100819.1 (28h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1240420
telemt_connections_bad_total 44150
telemt_handshake_timeouts_total 21610
telemt_upstream_connect_attempt_total 83435
telemt_upstream_connect_success_total 83003
telemt_upstream_connect_fail_total 432
telemt_upstream_connect_attempts_per_request{bucket="1"} 83435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 346
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 432
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 34933
telemt_me_reconnect_success_total 14610
telemt_me_reader_eof_total 16101
telemt_me_idle_close_by_peer_total 16099
telemt_me_route_drop_no_conn_total 512025
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1014155
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3805
telemt_desync_full_logged_total 1244
telemt_desync_suppressed_total 2561
telemt_desync_frames_bucket_total{bucket="1_2"} 932
telemt_desync_frames_bucket_total{bucket="3_10"} 1599
telemt_desync_frames_bucket_total{bucket="gt_10"} 1274
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 15515
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14601
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 905
telemt_user_connections_total{user="hello"} 1076645
telemt_user_connections_current{user="hello"} 718
telemt_user_octets_from_client{user="hello"} 16870765595 (15.71 GB)
telemt_user_octets_to_client{user="hello"} 478318909273 (445.47 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 100791.0 (27h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 798231
telemt_connections_bad_total 95009
telemt_handshake_timeouts_total 6440
telemt_upstream_connect_attempt_total 42360
telemt_upstream_connect_success_total 41789
telemt_upstream_connect_fail_total 571
telemt_upstream_connect_attempts_per_request{bucket="1"} 42360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 402
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 571
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 55236
telemt_me_reconnect_success_total 20283
telemt_me_reader_eof_total 22112
telemt_me_idle_close_by_peer_total 22110
telemt_me_route_drop_no_conn_total 252625
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 639435
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2935
telemt_desync_full_logged_total 866
telemt_desync_suppressed_total 2069
telemt_desync_frames_bucket_total{bucket="1_2"} 943
telemt_desync_frames_bucket_total{bucket="3_10"} 1177
telemt_desync_frames_bucket_total{bucket="gt_10"} 815
telemt_pool_swap_total 50
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21718
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 20275
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1435
telemt_user_connections_total{user="hello"} 656046
telemt_user_connections_current{user="hello"} 608
telemt_user_octets_from_client{user="hello"} 12548788692 (11.69 GB)
telemt_user_octets_to_client{user="hello"} 326272171432 (303.86 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 100951.9 (28h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1028753
telemt_connections_bad_total 85708
telemt_handshake_timeouts_total 9519
telemt_upstream_connect_attempt_total 19943
telemt_upstream_connect_success_total 19829
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 19943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10232
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26050
telemt_me_reconnect_success_total 14771
telemt_me_reader_eof_total 16040
telemt_me_idle_close_by_peer_total 16038
telemt_me_route_drop_no_conn_total 694287
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1005904
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2086
telemt_desync_full_logged_total 727
telemt_desync_suppressed_total 1359
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 789
telemt_desync_frames_bucket_total{bucket="gt_10"} 836
telemt_pool_swap_total 87
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15367
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14757
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 596
telemt_user_connections_total{user="hello"} 868932
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 13414536372 (12.49 GB)
telemt_user_octets_to_client{user="hello"} 369454852600 (344.08 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 48719.1 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 361671
telemt_connections_bad_total 44489
telemt_handshake_timeouts_total 10575
telemt_upstream_connect_attempt_total 18794
telemt_upstream_connect_success_total 18618
telemt_upstream_connect_fail_total 176
telemt_upstream_connect_attempts_per_request{bucket="1"} 18794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8573
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 176
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 27592
telemt_me_reconnect_success_total 15997
telemt_me_reader_eof_total 16909
telemt_me_idle_close_by_peer_total 16909
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 90336
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 273541
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 953
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 659
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 392
telemt_desync_frames_bucket_total{bucket="gt_10"} 349
telemt_pool_swap_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 16546
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15968
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 549
telemt_user_connections_total{user="hello"} 273479
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 21351572861 (19.89 GB)
telemt_user_octets_to_client{user="hello"} 224923983890 (209.48 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 33
```