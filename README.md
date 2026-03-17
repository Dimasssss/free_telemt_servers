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

# Server Metrics 2026-03-17 16:11:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 77166.8 (21h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 878948
telemt_connections_bad_total 6359
telemt_handshake_timeouts_total 25273
telemt_upstream_connect_attempt_total 18434
telemt_upstream_connect_success_total 17962
telemt_upstream_connect_fail_total 472
telemt_upstream_connect_attempts_per_request{bucket="1"} 18434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 472
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 27689
telemt_me_reconnect_success_total 11793
telemt_me_reader_eof_total 12842
telemt_me_idle_close_by_peer_total 12841
telemt_me_route_drop_no_conn_total 404831
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 807029
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5469
telemt_desync_full_logged_total 1514
telemt_desync_suppressed_total 3955
telemt_desync_frames_bucket_total{bucket="1_2"} 1581
telemt_desync_frames_bucket_total{bucket="3_10"} 2120
telemt_desync_frames_bucket_total{bucket="gt_10"} 1768
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 12448
telemt_me_refill_failed_total 491
telemt_me_writer_restored_same_endpoint_total 11771
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 655
telemt_user_connections_total{user="hello"} 801473
telemt_user_connections_current{user="hello"} 1433
telemt_user_octets_from_client{user="hello"} 12519772731 (11.66 GB)
telemt_user_octets_to_client{user="hello"} 262247020231 (244.24 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 77418.1 (21h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 588325
telemt_connections_bad_total 32407
telemt_handshake_timeouts_total 28593
telemt_upstream_connect_attempt_total 143353
telemt_upstream_connect_success_total 142777
telemt_upstream_connect_fail_total 574
telemt_upstream_connect_attempts_per_request{bucket="1"} 143351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14897
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10666
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 574
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 42911
telemt_me_reconnect_success_total 13524
telemt_me_reader_eof_total 14995
telemt_me_idle_close_by_peer_total 14995
telemt_me_route_drop_no_conn_total 196856
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375662
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1494
telemt_desync_full_logged_total 469
telemt_desync_suppressed_total 1025
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 651
telemt_desync_frames_bucket_total{bucket="gt_10"} 507
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14605
telemt_me_refill_failed_total 914
telemt_me_writer_restored_same_endpoint_total 13508
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1081
telemt_user_connections_total{user="hello"} 500950
telemt_user_connections_current{user="hello"} 958
telemt_user_octets_from_client{user="hello"} 5511309669 (5.13 GB)
telemt_user_octets_to_client{user="hello"} 139132626912 (129.58 GB)
telemt_user_msgs_from_client{user="hello"} 1830549
telemt_user_msgs_to_client{user="hello"} 6901481
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 77194.0 (21h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293443
telemt_connections_bad_total 7876
telemt_handshake_timeouts_total 19053
telemt_upstream_connect_attempt_total 19864
telemt_upstream_connect_success_total 19760
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 19864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10747
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 33725
telemt_me_reconnect_success_total 15838
telemt_me_reader_eof_total 17257
telemt_me_idle_close_by_peer_total 17254
telemt_me_route_drop_no_conn_total 140603
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251641
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 829
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 587
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16606
telemt_me_refill_failed_total 556
telemt_me_writer_restored_same_endpoint_total 15827
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 768
telemt_user_connections_total{user="hello"} 251488
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 19678543516 (18.33 GB)
telemt_user_octets_to_client{user="hello"} 60315318776 (56.17 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 77253.5 (21h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 702929
telemt_connections_bad_total 11368
telemt_handshake_timeouts_total 14868
telemt_upstream_connect_attempt_total 75799
telemt_upstream_connect_success_total 75434
telemt_upstream_connect_fail_total 365
telemt_upstream_connect_attempts_per_request{bucket="1"} 75799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10383
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 285
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 365
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 32291
telemt_me_reconnect_success_total 11999
telemt_me_reader_eof_total 13272
telemt_me_idle_close_by_peer_total 13271
telemt_me_route_drop_no_conn_total 259863
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547961
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1872
telemt_desync_full_logged_total 635
telemt_desync_suppressed_total 1237
telemt_desync_frames_bucket_total{bucket="1_2"} 474
telemt_desync_frames_bucket_total{bucket="3_10"} 841
telemt_desync_frames_bucket_total{bucket="gt_10"} 557
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12841
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 11990
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 842
telemt_user_connections_total{user="hello"} 607294
telemt_user_connections_current{user="hello"} 971
telemt_user_octets_from_client{user="hello"} 7152517469 (6.66 GB)
telemt_user_octets_to_client{user="hello"} 180583136274 (168.18 GB)
telemt_user_msgs_from_client{user="hello"} 677518
telemt_user_msgs_to_client{user="hello"} 4868613
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 77225.3 (21h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310951
telemt_connections_bad_total 58038
telemt_handshake_timeouts_total 3776
telemt_upstream_connect_attempt_total 21793
telemt_upstream_connect_success_total 21315
telemt_upstream_connect_fail_total 478
telemt_upstream_connect_attempts_per_request{bucket="1"} 21793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 296
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 478
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 47020
telemt_me_reconnect_success_total 17044
telemt_me_reader_eof_total 18569
telemt_me_idle_close_by_peer_total 18567
telemt_me_route_drop_no_conn_total 90477
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236103
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1146
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 898
telemt_desync_frames_bucket_total{bucket="1_2"} 573
telemt_desync_frames_bucket_total{bucket="3_10"} 443
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 18261
telemt_me_refill_failed_total 932
telemt_me_writer_restored_same_endpoint_total 17036
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1217
telemt_user_connections_total{user="hello"} 236663
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 2886700011 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 86208974727 (80.29 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 77387.8 (21h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 760521
telemt_connections_bad_total 60180
telemt_handshake_timeouts_total 7188
telemt_upstream_connect_attempt_total 15541
telemt_upstream_connect_success_total 15458
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7939
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 21883
telemt_me_reconnect_success_total 11582
telemt_me_reader_eof_total 12601
telemt_me_idle_close_by_peer_total 12600
telemt_me_route_drop_no_conn_total 562960
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 777751
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1206
telemt_desync_full_logged_total 431
telemt_desync_suppressed_total 775
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 475
telemt_desync_frames_bucket_total{bucket="gt_10"} 442
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12092
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 11568
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 655165
telemt_user_connections_current{user="hello"} 954
telemt_user_octets_from_client{user="hello"} 9482732656 (8.83 GB)
telemt_user_octets_to_client{user="hello"} 293307574636 (273.16 GB)
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 25153.4 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19546
telemt_connections_bad_total 86
telemt_handshake_timeouts_total 315
telemt_upstream_connect_attempt_total 13390
telemt_upstream_connect_success_total 13279
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 13390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6049
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 23417
telemt_me_reconnect_success_total 11847
telemt_me_reader_eof_total 12543
telemt_me_idle_close_by_peer_total 12543
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 9736
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18680
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 12341
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 11827
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 494
telemt_user_connections_total{user="hello"} 18734
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 625992129 (596.99 MB)
telemt_user_octets_to_client{user="hello"} 25654654858 (23.89 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 9
```