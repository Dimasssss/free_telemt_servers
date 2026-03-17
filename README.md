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

# Server Metrics 2026-03-17 21:42:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 97054.8 (26h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1189446
telemt_connections_bad_total 8641
telemt_handshake_timeouts_total 31562
telemt_upstream_connect_attempt_total 22013
telemt_upstream_connect_success_total 21522
telemt_upstream_connect_fail_total 491
telemt_upstream_connect_attempts_per_request{bucket="1"} 22013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31515
telemt_me_reconnect_success_total 14385
telemt_me_reader_eof_total 15632
telemt_me_idle_close_by_peer_total 15631
telemt_me_route_drop_no_conn_total 530528
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1090714
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7200
telemt_desync_full_logged_total 2078
telemt_desync_suppressed_total 5122
telemt_desync_frames_bucket_total{bucket="1_2"} 1929
telemt_desync_frames_bucket_total{bucket="3_10"} 2726
telemt_desync_frames_bucket_total{bucket="gt_10"} 2545
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 15132
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14363
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 747
telemt_user_connections_total{user="hello"} 1084947
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 19493195883 (18.15 GB)
telemt_user_octets_to_client{user="hello"} 385069207163 (358.62 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 97306.2 (27h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1246009
telemt_connections_bad_total 59647
telemt_handshake_timeouts_total 44347
telemt_upstream_connect_attempt_total 457506
telemt_upstream_connect_success_total 456611
telemt_upstream_connect_fail_total 895
telemt_upstream_connect_attempts_per_request{bucket="1"} 457506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30530
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 895
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57885
telemt_me_reconnect_success_total 14732
telemt_me_reader_eof_total 16706
telemt_me_idle_close_by_peer_total 16706
telemt_me_route_drop_no_conn_total 318608
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 640735
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2817
telemt_desync_full_logged_total 904
telemt_desync_suppressed_total 1913
telemt_desync_frames_bucket_total{bucket="1_2"} 533
telemt_desync_frames_bucket_total{bucket="3_10"} 1169
telemt_desync_frames_bucket_total{bucket="gt_10"} 1115
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 16263
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14716
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1531
telemt_user_connections_total{user="hello"} 1077165
telemt_user_connections_current{user="hello"} 1087
telemt_user_octets_from_client{user="hello"} 14862419374 (13.84 GB)
telemt_user_octets_to_client{user="hello"} 361310929586 (336.50 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 348
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 97082.4 (26h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 706417
telemt_connections_bad_total 41746
telemt_handshake_timeouts_total 22676
telemt_upstream_connect_attempt_total 23103
telemt_upstream_connect_success_total 22968
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 23103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12364
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38755
telemt_me_reconnect_success_total 18079
telemt_me_reader_eof_total 19724
telemt_me_idle_close_by_peer_total 19717
telemt_me_route_drop_no_conn_total 296718
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 608287
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1960
telemt_desync_full_logged_total 596
telemt_desync_suppressed_total 1364
telemt_desync_frames_bucket_total{bucket="1_2"} 546
telemt_desync_frames_bucket_total{bucket="3_10"} 771
telemt_desync_frames_bucket_total{bucket="gt_10"} 643
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18972
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18067
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 893
telemt_user_connections_total{user="hello"} 606558
telemt_user_connections_current{user="hello"} 818
telemt_user_octets_from_client{user="hello"} 30500083908 (28.41 GB)
telemt_user_octets_to_client{user="hello"} 264357504268 (246.20 GB)
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 97141.6 (26h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1206189
telemt_connections_bad_total 38620
telemt_handshake_timeouts_total 21380
telemt_upstream_connect_attempt_total 82725
telemt_upstream_connect_success_total 82299
telemt_upstream_connect_fail_total 426
telemt_upstream_connect_attempts_per_request{bucket="1"} 82725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12080
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 426
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 34402
telemt_me_reconnect_success_total 14082
telemt_me_reader_eof_total 15539
telemt_me_idle_close_by_peer_total 15537
telemt_me_route_drop_no_conn_total 500024
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 986374
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3475
telemt_desync_full_logged_total 1120
telemt_desync_suppressed_total 2355
telemt_desync_frames_bucket_total{bucket="1_2"} 856
telemt_desync_frames_bucket_total{bucket="3_10"} 1461
telemt_desync_frames_bucket_total{bucket="gt_10"} 1158
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 14981
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14073
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 899
telemt_user_connections_total{user="hello"} 1048872
telemt_user_connections_current{user="hello"} 998
telemt_user_octets_from_client{user="hello"} 16452383415 (15.32 GB)
telemt_user_octets_to_client{user="hello"} 449467191161 (418.60 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 97113.6 (26h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 761906
telemt_connections_bad_total 91448
telemt_handshake_timeouts_total 6372
telemt_upstream_connect_attempt_total 41672
telemt_upstream_connect_success_total 41115
telemt_upstream_connect_fail_total 557
telemt_upstream_connect_attempts_per_request{bucket="1"} 41672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14360
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 398
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 557
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 52270
telemt_me_reconnect_success_total 19784
telemt_me_reader_eof_total 21514
telemt_me_idle_close_by_peer_total 21512
telemt_me_route_drop_no_conn_total 239417
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 607560
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2784
telemt_desync_full_logged_total 817
telemt_desync_suppressed_total 1967
telemt_desync_frames_bucket_total{bucket="1_2"} 891
telemt_desync_frames_bucket_total{bucket="3_10"} 1119
telemt_desync_frames_bucket_total{bucket="gt_10"} 774
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21132
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 19776
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1348
telemt_user_connections_total{user="hello"} 624174
telemt_user_connections_current{user="hello"} 816
telemt_user_octets_from_client{user="hello"} 12059922112 (11.23 GB)
telemt_user_octets_to_client{user="hello"} 306466608952 (285.42 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 97274.5 (27h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 999628
telemt_connections_bad_total 75777
telemt_handshake_timeouts_total 9398
telemt_upstream_connect_attempt_total 19207
telemt_upstream_connect_success_total 19095
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 19207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9851
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25499
telemt_me_reconnect_success_total 14221
telemt_me_reader_eof_total 15446
telemt_me_idle_close_by_peer_total 15444
telemt_me_route_drop_no_conn_total 685929
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 989303
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2046
telemt_desync_full_logged_total 712
telemt_desync_suppressed_total 1334
telemt_desync_frames_bucket_total{bucket="1_2"} 459
telemt_desync_frames_bucket_total{bucket="3_10"} 776
telemt_desync_frames_bucket_total{bucket="gt_10"} 811
telemt_pool_swap_total 82
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 14809
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14207
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 852335
telemt_user_connections_current{user="hello"} 475
telemt_user_octets_from_client{user="hello"} 13302362684 (12.39 GB)
telemt_user_octets_to_client{user="hello"} 363845347940 (338.86 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 45041.7 (12h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337635
telemt_connections_bad_total 43330
telemt_handshake_timeouts_total 10524
telemt_upstream_connect_attempt_total 17902
telemt_upstream_connect_success_total 17738
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 17902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26918
telemt_me_reconnect_success_total 15325
telemt_me_reader_eof_total 16191
telemt_me_idle_close_by_peer_total 16191
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 82852
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257271
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 832
telemt_desync_full_logged_total 245
telemt_desync_suppressed_total 587
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 326
telemt_desync_frames_bucket_total{bucket="gt_10"} 302
telemt_pool_swap_total 23
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15865
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15297
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 540
telemt_user_connections_total{user="hello"} 257212
telemt_user_connections_current{user="hello"} 517
telemt_user_octets_from_client{user="hello"} 21086056017 (19.64 GB)
telemt_user_octets_to_client{user="hello"} 214639058978 (199.90 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 52
```