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

# Server Metrics 2026-03-17 21:12:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 95216.4 (26h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1173435
telemt_connections_bad_total 8633
telemt_handshake_timeouts_total 31347
telemt_upstream_connect_attempt_total 21644
telemt_upstream_connect_success_total 21154
telemt_upstream_connect_fail_total 490
telemt_upstream_connect_attempts_per_request{bucket="1"} 21644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 490
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31233
telemt_me_reconnect_success_total 14103
telemt_me_reader_eof_total 15329
telemt_me_idle_close_by_peer_total 15328
telemt_me_route_drop_no_conn_total 524385
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1075437
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7155
telemt_desync_full_logged_total 2056
telemt_desync_suppressed_total 5099
telemt_desync_frames_bucket_total{bucket="1_2"} 1917
telemt_desync_frames_bucket_total{bucket="3_10"} 2712
telemt_desync_frames_bucket_total{bucket="gt_10"} 2526
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 14847
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14081
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 744
telemt_user_connections_total{user="hello"} 1069673
telemt_user_connections_current{user="hello"} 657
telemt_user_octets_from_client{user="hello"} 19103638823 (17.79 GB)
telemt_user_octets_to_client{user="hello"} 379983133395 (353.89 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 95467.7 (26h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1216817
telemt_connections_bad_total 59543
telemt_handshake_timeouts_total 43865
telemt_upstream_connect_attempt_total 457152
telemt_upstream_connect_success_total 456267
telemt_upstream_connect_fail_total 885
telemt_upstream_connect_attempts_per_request{bucket="1"} 457152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30353
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 885
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57643
telemt_me_reconnect_success_total 14490
telemt_me_reader_eof_total 16452
telemt_me_idle_close_by_peer_total 16452
telemt_me_route_drop_no_conn_total 308908
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 613139
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2722
telemt_desync_full_logged_total 864
telemt_desync_suppressed_total 1858
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 1135
telemt_desync_frames_bucket_total{bucket="gt_10"} 1071
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 16020
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14474
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1530
telemt_user_connections_total{user="hello"} 1049566
telemt_user_connections_current{user="hello"} 1277
telemt_user_octets_from_client{user="hello"} 14558443146 (13.56 GB)
telemt_user_octets_to_client{user="hello"} 349573743182 (325.57 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 383
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 95243.6 (26h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 682929
telemt_connections_bad_total 39260
telemt_handshake_timeouts_total 22552
telemt_upstream_connect_attempt_total 22785
telemt_upstream_connect_success_total 22654
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 22785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12199
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38527
telemt_me_reconnect_success_total 17852
telemt_me_reader_eof_total 19484
telemt_me_idle_close_by_peer_total 19477
telemt_me_route_drop_no_conn_total 289223
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 588359
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1878
telemt_desync_full_logged_total 571
telemt_desync_suppressed_total 1307
telemt_desync_frames_bucket_total{bucket="1_2"} 525
telemt_desync_frames_bucket_total{bucket="3_10"} 734
telemt_desync_frames_bucket_total{bucket="gt_10"} 619
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 18742
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17840
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 890
telemt_user_connections_total{user="hello"} 586630
telemt_user_connections_current{user="hello"} 933
telemt_user_octets_from_client{user="hello"} 28917760848 (26.93 GB)
telemt_user_octets_to_client{user="hello"} 248041449472 (231.01 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 95302.9 (26h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1184663
telemt_connections_bad_total 36819
telemt_handshake_timeouts_total 21241
telemt_upstream_connect_attempt_total 82358
telemt_upstream_connect_success_total 81942
telemt_upstream_connect_fail_total 416
telemt_upstream_connect_attempts_per_request{bucket="1"} 82358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11887
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 342
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 416
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 34127
telemt_me_reconnect_success_total 13812
telemt_me_reader_eof_total 15218
telemt_me_idle_close_by_peer_total 15217
telemt_me_route_drop_no_conn_total 492524
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 967340
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3324
telemt_desync_full_logged_total 1061
telemt_desync_suppressed_total 2263
telemt_desync_frames_bucket_total{bucket="1_2"} 818
telemt_desync_frames_bucket_total{bucket="3_10"} 1407
telemt_desync_frames_bucket_total{bucket="gt_10"} 1099
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 14704
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13803
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 892
telemt_user_connections_total{user="hello"} 1029851
telemt_user_connections_current{user="hello"} 1127
telemt_user_octets_from_client{user="hello"} 15390493123 (14.33 GB)
telemt_user_octets_to_client{user="hello"} 432504461565 (402.80 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 95274.9 (26h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 737426
telemt_connections_bad_total 90785
telemt_handshake_timeouts_total 6247
telemt_upstream_connect_attempt_total 41170
telemt_upstream_connect_success_total 40623
telemt_upstream_connect_fail_total 547
telemt_upstream_connect_attempts_per_request{bucket="1"} 41170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 394
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 547
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51864
telemt_me_reconnect_success_total 19379
telemt_me_reader_eof_total 21106
telemt_me_idle_close_by_peer_total 21104
telemt_me_route_drop_no_conn_total 231306
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 584389
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2690
telemt_desync_full_logged_total 779
telemt_desync_suppressed_total 1911
telemt_desync_frames_bucket_total{bucket="1_2"} 883
telemt_desync_frames_bucket_total{bucket="3_10"} 1076
telemt_desync_frames_bucket_total{bucket="gt_10"} 731
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20724
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 19371
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1345
telemt_user_connections_total{user="hello"} 601003
telemt_user_connections_current{user="hello"} 1026
telemt_user_octets_from_client{user="hello"} 11755630308 (10.95 GB)
telemt_user_octets_to_client{user="hello"} 294192829612 (273.99 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 95436.0 (26h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 982119
telemt_connections_bad_total 70834
telemt_handshake_timeouts_total 9299
telemt_upstream_connect_attempt_total 18848
telemt_upstream_connect_success_total 18738
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 18848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9684
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25251
telemt_me_reconnect_success_total 13974
telemt_me_reader_eof_total 15179
telemt_me_idle_close_by_peer_total 15177
telemt_me_route_drop_no_conn_total 681528
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 978354
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2011
telemt_desync_full_logged_total 701
telemt_desync_suppressed_total 1310
telemt_desync_frames_bucket_total{bucket="1_2"} 453
telemt_desync_frames_bucket_total{bucket="3_10"} 766
telemt_desync_frames_bucket_total{bucket="gt_10"} 792
telemt_pool_swap_total 80
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14557
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13960
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 841387
telemt_user_connections_current{user="hello"} 509
telemt_user_octets_from_client{user="hello"} 13005616532 (12.11 GB)
telemt_user_octets_to_client{user="hello"} 361861727208 (337.01 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 43203.1 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 316667
telemt_connections_bad_total 41160
telemt_handshake_timeouts_total 9561
telemt_upstream_connect_attempt_total 17485
telemt_upstream_connect_success_total 17324
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 17485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26600
telemt_me_reconnect_success_total 15007
telemt_me_reader_eof_total 15857
telemt_me_idle_close_by_peer_total 15857
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 77941
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242786
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 766
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 548
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 295
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 21
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15546
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 14979
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 539
telemt_user_connections_total{user="hello"} 242729
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 20870370101 (19.44 GB)
telemt_user_octets_to_client{user="hello"} 203468598410 (189.49 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 57
```