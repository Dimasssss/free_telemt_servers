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

# Server Metrics 2026-03-17 19:25:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 88790.7 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1095119
telemt_connections_bad_total 7851
telemt_handshake_timeouts_total 29991
telemt_upstream_connect_attempt_total 20555
telemt_upstream_connect_success_total 20067
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 20555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 30447
telemt_me_reconnect_success_total 13320
telemt_me_reader_eof_total 14489
telemt_me_idle_close_by_peer_total 14488
telemt_me_route_drop_no_conn_total 494748
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1002751
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6596
telemt_desync_full_logged_total 1883
telemt_desync_suppressed_total 4713
telemt_desync_frames_bucket_total{bucket="1_2"} 1794
telemt_desync_frames_bucket_total{bucket="3_10"} 2520
telemt_desync_frames_bucket_total{bucket="gt_10"} 2282
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 14049
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13298
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 729
telemt_user_connections_total{user="hello"} 996998
telemt_user_connections_current{user="hello"} 1003
telemt_user_octets_from_client{user="hello"} 15111191815 (14.07 GB)
telemt_user_octets_to_client{user="hello"} 347038610623 (323.20 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 89042.1 (24h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1077490
telemt_connections_bad_total 56610
telemt_handshake_timeouts_total 37277
telemt_upstream_connect_attempt_total 456154
telemt_upstream_connect_success_total 455285
telemt_upstream_connect_fail_total 869
telemt_upstream_connect_attempts_per_request{bucket="1"} 456154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29829
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 869
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 56987
telemt_me_reconnect_success_total 13837
telemt_me_reader_eof_total 15749
telemt_me_idle_close_by_peer_total 15749
telemt_me_route_drop_no_conn_total 264676
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 487974
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1922
telemt_desync_full_logged_total 616
telemt_desync_suppressed_total 1306
telemt_desync_frames_bucket_total{bucket="1_2"} 421
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 691
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 15351
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 13821
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1514
telemt_user_connections_total{user="hello"} 924414
telemt_user_connections_current{user="hello"} 1431
telemt_user_octets_from_client{user="hello"} 12775276218 (11.90 GB)
telemt_user_octets_to_client{user="hello"} 273581175722 (254.79 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 421
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 88818.1 (24h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 565624
telemt_connections_bad_total 21169
telemt_handshake_timeouts_total 21862
telemt_upstream_connect_attempt_total 21680
telemt_upstream_connect_success_total 21557
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 21680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11650
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 37733
telemt_me_reconnect_success_total 17062
telemt_me_reader_eof_total 18649
telemt_me_idle_close_by_peer_total 18642
telemt_me_route_drop_no_conn_total 253434
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 495102
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1428
telemt_desync_full_logged_total 419
telemt_desync_suppressed_total 1009
telemt_desync_frames_bucket_total{bucket="1_2"} 423
telemt_desync_frames_bucket_total{bucket="3_10"} 586
telemt_desync_frames_bucket_total{bucket="gt_10"} 419
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 17937
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17050
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 875
telemt_user_connections_total{user="hello"} 493324
telemt_user_connections_current{user="hello"} 1050
telemt_user_octets_from_client{user="hello"} 27391059224 (25.51 GB)
telemt_user_octets_to_client{user="hello"} 190971066204 (177.86 GB)
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 88877.4 (24h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1062278
telemt_connections_bad_total 26802
telemt_handshake_timeouts_total 20361
telemt_upstream_connect_attempt_total 81334
telemt_upstream_connect_success_total 80931
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 81334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11352
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33414
telemt_me_reconnect_success_total 13111
telemt_me_reader_eof_total 14465
telemt_me_idle_close_by_peer_total 14464
telemt_me_route_drop_no_conn_total 439675
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 860049
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2834
telemt_desync_full_logged_total 920
telemt_desync_suppressed_total 1914
telemt_desync_frames_bucket_total{bucket="1_2"} 675
telemt_desync_frames_bucket_total{bucket="3_10"} 1235
telemt_desync_frames_bucket_total{bucket="gt_10"} 924
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 13986
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13102
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 875
telemt_user_connections_total{user="hello"} 923113
telemt_user_connections_current{user="hello"} 1556
telemt_user_octets_from_client{user="hello"} 13102681615 (12.20 GB)
telemt_user_octets_to_client{user="hello"} 348362342093 (324.44 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 88849.3 (24h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 619347
telemt_connections_bad_total 75977
telemt_handshake_timeouts_total 5311
telemt_upstream_connect_attempt_total 39990
telemt_upstream_connect_success_total 39459
telemt_upstream_connect_fail_total 531
telemt_upstream_connect_attempts_per_request{bucket="1"} 39990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 531
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 51002
telemt_me_reconnect_success_total 18520
telemt_me_reader_eof_total 20196
telemt_me_idle_close_by_peer_total 20194
telemt_me_route_drop_no_conn_total 191771
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 486717
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2183
telemt_desync_full_logged_total 584
telemt_desync_suppressed_total 1599
telemt_desync_frames_bucket_total{bucket="1_2"} 781
telemt_desync_frames_bucket_total{bucket="3_10"} 860
telemt_desync_frames_bucket_total{bucket="gt_10"} 542
telemt_pool_swap_total 43
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19852
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18512
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1332
telemt_user_connections_total{user="hello"} 503370
telemt_user_connections_current{user="hello"} 1241
telemt_user_octets_from_client{user="hello"} 10185519424 (9.49 GB)
telemt_user_octets_to_client{user="hello"} 234795210584 (218.67 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 380
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 89010.7 (24h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 911169
telemt_connections_bad_total 61552
telemt_handshake_timeouts_total 8896
telemt_upstream_connect_attempt_total 17679
telemt_upstream_connect_success_total 17580
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 17679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9093
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 24404
telemt_me_reconnect_success_total 13130
telemt_me_reader_eof_total 14274
telemt_me_idle_close_by_peer_total 14272
telemt_me_route_drop_no_conn_total 655571
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 926558
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1819
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1191
telemt_desync_frames_bucket_total{bucket="1_2"} 437
telemt_desync_frames_bucket_total{bucket="3_10"} 697
telemt_desync_frames_bucket_total{bucket="gt_10"} 685
telemt_pool_swap_total 73
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13704
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13116
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 574
telemt_user_connections_total{user="hello"} 789598
telemt_user_connections_current{user="hello"} 775
telemt_user_octets_from_client{user="hello"} 12111976252 (11.28 GB)
telemt_user_octets_to_client{user="hello"} 341923605568 (318.44 GB)
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 36777.4 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240668
telemt_connections_bad_total 31401
telemt_handshake_timeouts_total 6264
telemt_upstream_connect_attempt_total 15975
telemt_upstream_connect_success_total 15837
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 15975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7257
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 25413
telemt_me_reconnect_success_total 13826
telemt_me_reader_eof_total 14614
telemt_me_idle_close_by_peer_total 14614
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 57947
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184692
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 570
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 421
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 216
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 16
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14353
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 13801
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 527
telemt_user_connections_total{user="hello"} 184633
telemt_user_connections_current{user="hello"} 742
telemt_user_octets_from_client{user="hello"} 17703711381 (16.49 GB)
telemt_user_octets_to_client{user="hello"} 156442808882 (145.70 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 81
```