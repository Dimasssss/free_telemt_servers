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

# Server Metrics 2026-03-17 17:38:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 82368.5 (22h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 992166
telemt_connections_bad_total 6536
telemt_handshake_timeouts_total 27868
telemt_upstream_connect_attempt_total 19494
telemt_upstream_connect_success_total 19015
telemt_upstream_connect_fail_total 479
telemt_upstream_connect_attempts_per_request{bucket="1"} 19494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8934
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 479
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 29698
telemt_me_reconnect_success_total 12582
telemt_me_reader_eof_total 13710
telemt_me_idle_close_by_peer_total 13709
telemt_me_route_drop_no_conn_total 453340
telemt_me_route_drop_channel_closed_total 123
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 907560
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6043
telemt_desync_full_logged_total 1714
telemt_desync_suppressed_total 4329
telemt_desync_frames_bucket_total{bucket="1_2"} 1674
telemt_desync_frames_bucket_total{bucket="3_10"} 2322
telemt_desync_frames_bucket_total{bucket="gt_10"} 2047
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 13293
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12560
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 711
telemt_user_connections_total{user="hello"} 901816
telemt_user_connections_current{user="hello"} 1144
telemt_user_octets_from_client{user="hello"} 13823882827 (12.87 GB)
telemt_user_octets_to_client{user="hello"} 308611265975 (287.42 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 377
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 82620.8 (22h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 849521
telemt_connections_bad_total 50381
telemt_handshake_timeouts_total 31493
telemt_upstream_connect_attempt_total 335404
telemt_upstream_connect_success_total 334640
telemt_upstream_connect_fail_total 759
telemt_upstream_connect_attempts_per_request{bucket="1"} 335399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 277612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24977
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32049
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 759
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 51210
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15294
telemt_me_idle_close_by_peer_total 15294
telemt_me_route_drop_no_conn_total 235089
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 413159
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1549
telemt_desync_full_logged_total 491
telemt_desync_suppressed_total 1058
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 674
telemt_desync_frames_bucket_total{bucket="gt_10"} 524
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14904
telemt_me_refill_failed_total 1172
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1339
telemt_user_connections_total{user="hello"} 729993
telemt_user_connections_current{user="hello"} 1924
telemt_user_octets_from_client{user="hello"} 9817150648 (9.14 GB)
telemt_user_octets_to_client{user="hello"} 197559071327 (183.99 GB)
telemt_user_msgs_from_client{user="hello"} 5345912
telemt_user_msgs_to_client{user="hello"} 22329244
telemt_user_unique_ips_current{user="hello"} 452
telemt_user_unique_ips_recent_window{user="hello"} 266
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 82396.2 (22h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 437026
telemt_connections_bad_total 13902
telemt_handshake_timeouts_total 20618
telemt_upstream_connect_attempt_total 20633
telemt_upstream_connect_success_total 20515
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 20633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11106
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 36995
telemt_me_reconnect_success_total 16327
telemt_me_reader_eof_total 17864
telemt_me_idle_close_by_peer_total 17857
telemt_me_route_drop_no_conn_total 209020
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 381070
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1068
telemt_desync_full_logged_total 323
telemt_desync_suppressed_total 745
telemt_desync_frames_bucket_total{bucket="1_2"} 359
telemt_desync_frames_bucket_total{bucket="3_10"} 460
telemt_desync_frames_bucket_total{bucket="gt_10"} 249
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 17193
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16315
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 866
telemt_user_connections_total{user="hello"} 379222
telemt_user_connections_current{user="hello"} 1382
telemt_user_octets_from_client{user="hello"} 24896943388 (23.19 GB)
telemt_user_octets_to_client{user="hello"} 134393028784 (125.16 GB)
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 82455.5 (22h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 907189
telemt_connections_bad_total 20650
telemt_handshake_timeouts_total 17689
telemt_upstream_connect_attempt_total 80396
telemt_upstream_connect_success_total 80000
telemt_upstream_connect_fail_total 396
telemt_upstream_connect_attempts_per_request{bucket="1"} 80396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 330
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 396
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 32785
telemt_me_reconnect_success_total 12485
telemt_me_reader_eof_total 13793
telemt_me_idle_close_by_peer_total 13792
telemt_me_route_drop_no_conn_total 384942
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 725193
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2344
telemt_desync_full_logged_total 751
telemt_desync_suppressed_total 1593
telemt_desync_frames_bucket_total{bucket="1_2"} 561
telemt_desync_frames_bucket_total{bucket="3_10"} 1049
telemt_desync_frames_bucket_total{bucket="gt_10"} 734
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 13346
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12476
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 861
telemt_user_connections_total{user="hello"} 788302
telemt_user_connections_current{user="hello"} 1861
telemt_user_octets_from_client{user="hello"} 9571713655 (8.91 GB)
telemt_user_octets_to_client{user="hello"} 258699736949 (240.93 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 82427.2 (22h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478980
telemt_connections_bad_total 71674
telemt_handshake_timeouts_total 4486
telemt_upstream_connect_attempt_total 38793
telemt_upstream_connect_success_total 38292
telemt_upstream_connect_fail_total 501
telemt_upstream_connect_attempts_per_request{bucket="1"} 38793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 501
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50137
telemt_me_reconnect_success_total 17659
telemt_me_reader_eof_total 19282
telemt_me_idle_close_by_peer_total 19280
telemt_me_route_drop_no_conn_total 141178
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 363718
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1599
telemt_desync_full_logged_total 395
telemt_desync_suppressed_total 1204
telemt_desync_frames_bucket_total{bucket="1_2"} 654
telemt_desync_frames_bucket_total{bucket="3_10"} 636
telemt_desync_frames_bucket_total{bucket="gt_10"} 309
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18967
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 17651
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1308
telemt_user_connections_total{user="hello"} 380421
telemt_user_connections_current{user="hello"} 1764
telemt_user_octets_from_client{user="hello"} 6298467252 (5.87 GB)
telemt_user_octets_to_client{user="hello"} 170698646280 (158.98 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 451
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 82589.2 (22h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 837312
telemt_connections_bad_total 60469
telemt_handshake_timeouts_total 7981
telemt_upstream_connect_attempt_total 16589
telemt_upstream_connect_success_total 16497
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 16589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8525
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 23623
telemt_me_reconnect_success_total 12354
telemt_me_reader_eof_total 13446
telemt_me_idle_close_by_peer_total 13444
telemt_me_route_drop_no_conn_total 623330
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 861567
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1539
telemt_desync_full_logged_total 532
telemt_desync_suppressed_total 1007
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 598
telemt_desync_frames_bucket_total{bucket="gt_10"} 570
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 12916
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12340
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 562
telemt_user_connections_total{user="hello"} 724630
telemt_user_connections_current{user="hello"} 873
telemt_user_octets_from_client{user="hello"} 10959430836 (10.21 GB)
telemt_user_octets_to_client{user="hello"} 318160420792 (296.31 GB)
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 30355.4 (8h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129861
telemt_connections_bad_total 11721
telemt_handshake_timeouts_total 4503
telemt_upstream_connect_attempt_total 14397
telemt_upstream_connect_success_total 14272
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 14397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6536
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24152
telemt_me_reconnect_success_total 12576
telemt_me_reader_eof_total 13319
telemt_me_idle_close_by_peer_total 13319
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 32054
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106534
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 156
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 13088
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12553
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 106502
telemt_user_connections_current{user="hello"} 1047
telemt_user_octets_from_client{user="hello"} 6589706469 (6.14 GB)
telemt_user_octets_to_client{user="hello"} 107202171310 (99.84 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 119
```