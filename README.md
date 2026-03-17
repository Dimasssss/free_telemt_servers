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

# Server Metrics 2026-03-17 23:04:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 101955.9 (28h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1224036
telemt_connections_bad_total 8817
telemt_handshake_timeouts_total 32238
telemt_upstream_connect_attempt_total 23016
telemt_upstream_connect_success_total 22521
telemt_upstream_connect_fail_total 495
telemt_upstream_connect_attempts_per_request{bucket="1"} 23016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 495
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32256
telemt_me_reconnect_success_total 15124
telemt_me_reader_eof_total 16431
telemt_me_idle_close_by_peer_total 16430
telemt_me_route_drop_no_conn_total 543909
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1123757
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7411
telemt_desync_full_logged_total 2154
telemt_desync_suppressed_total 5257
telemt_desync_frames_bucket_total{bucket="1_2"} 1982
telemt_desync_frames_bucket_total{bucket="3_10"} 2803
telemt_desync_frames_bucket_total{bucket="gt_10"} 2626
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 15878
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15102
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 754
telemt_user_connections_total{user="hello"} 1117981
telemt_user_connections_current{user="hello"} 527
telemt_user_octets_from_client{user="hello"} 20928380939 (19.49 GB)
telemt_user_octets_to_client{user="hello"} 403631472483 (375.91 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 102207.3 (28h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1295991
telemt_connections_bad_total 60626
telemt_handshake_timeouts_total 45165
telemt_upstream_connect_attempt_total 458474
telemt_upstream_connect_success_total 457567
telemt_upstream_connect_fail_total 907
telemt_upstream_connect_attempts_per_request{bucket="1"} 458474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31062
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 907
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58620
telemt_me_reconnect_success_total 15463
telemt_me_reader_eof_total 17487
telemt_me_idle_close_by_peer_total 17487
telemt_me_route_drop_no_conn_total 336610
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 688150
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3152
telemt_desync_full_logged_total 1031
telemt_desync_suppressed_total 2121
telemt_desync_frames_bucket_total{bucket="1_2"} 621
telemt_desync_frames_bucket_total{bucket="3_10"} 1289
telemt_desync_frames_bucket_total{bucket="gt_10"} 1242
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 17002
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15447
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1539
telemt_user_connections_total{user="hello"} 1124579
telemt_user_connections_current{user="hello"} 801
telemt_user_octets_from_client{user="hello"} 15475952690 (14.41 GB)
telemt_user_octets_to_client{user="hello"} 385298304370 (358.84 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 101983.4 (28h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 758107
telemt_connections_bad_total 47432
telemt_handshake_timeouts_total 23563
telemt_upstream_connect_attempt_total 24112
telemt_upstream_connect_success_total 23973
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 24112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12874
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39500
telemt_me_reconnect_success_total 18819
telemt_me_reader_eof_total 20518
telemt_me_idle_close_by_peer_total 20511
telemt_me_route_drop_no_conn_total 311476
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 645944
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2111
telemt_desync_full_logged_total 680
telemt_desync_suppressed_total 1431
telemt_desync_frames_bucket_total{bucket="1_2"} 592
telemt_desync_frames_bucket_total{bucket="3_10"} 818
telemt_desync_frames_bucket_total{bucket="gt_10"} 701
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 19722
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18807
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 903
telemt_user_connections_total{user="hello"} 644205
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 31384051948 (29.23 GB)
telemt_user_octets_to_client{user="hello"} 283396467692 (263.93 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 102042.9 (28h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1248686
telemt_connections_bad_total 45332
telemt_handshake_timeouts_total 21633
telemt_upstream_connect_attempt_total 83703
telemt_upstream_connect_success_total 83268
telemt_upstream_connect_fail_total 435
telemt_upstream_connect_attempts_per_request{bucket="1"} 83703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12570
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 435
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35114
telemt_me_reconnect_success_total 14789
telemt_me_reader_eof_total 16296
telemt_me_idle_close_by_peer_total 16294
telemt_me_route_drop_no_conn_total 514586
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1020758
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3832
telemt_desync_full_logged_total 1257
telemt_desync_suppressed_total 2575
telemt_desync_frames_bucket_total{bucket="1_2"} 941
telemt_desync_frames_bucket_total{bucket="3_10"} 1609
telemt_desync_frames_bucket_total{bucket="gt_10"} 1282
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 15698
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14780
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 909
telemt_user_connections_total{user="hello"} 1083244
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 16981838419 (15.82 GB)
telemt_user_octets_to_client{user="hello"} 485716487981 (452.36 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 102014.8 (28h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806349
telemt_connections_bad_total 95831
telemt_handshake_timeouts_total 6459
telemt_upstream_connect_attempt_total 42805
telemt_upstream_connect_success_total 42219
telemt_upstream_connect_fail_total 586
telemt_upstream_connect_attempts_per_request{bucket="1"} 42805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 404
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 586
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 55580
telemt_me_reconnect_success_total 20627
telemt_me_reader_eof_total 22462
telemt_me_idle_close_by_peer_total 22460
telemt_me_route_drop_no_conn_total 255986
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 646572
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2988
telemt_desync_full_logged_total 880
telemt_desync_suppressed_total 2108
telemt_desync_frames_bucket_total{bucket="1_2"} 966
telemt_desync_frames_bucket_total{bucket="3_10"} 1194
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 50
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22068
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 20619
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1441
telemt_user_connections_total{user="hello"} 663182
telemt_user_connections_current{user="hello"} 555
telemt_user_octets_from_client{user="hello"} 12667813096 (11.80 GB)
telemt_user_octets_to_client{user="hello"} 329546692916 (306.91 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 102175.8 (28h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1037510
telemt_connections_bad_total 88973
telemt_handshake_timeouts_total 9531
telemt_upstream_connect_attempt_total 20219
telemt_upstream_connect_success_total 20105
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 20219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10390
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26283
telemt_me_reconnect_success_total 15003
telemt_me_reader_eof_total 16289
telemt_me_idle_close_by_peer_total 16287
telemt_me_route_drop_no_conn_total 697461
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1010637
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2101
telemt_desync_full_logged_total 735
telemt_desync_suppressed_total 1366
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 798
telemt_desync_frames_bucket_total{bucket="gt_10"} 842
telemt_pool_swap_total 88
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15602
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14989
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 599
telemt_user_connections_total{user="hello"} 873663
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 13960228712 (13.00 GB)
telemt_user_octets_to_client{user="hello"} 370386440796 (344.95 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 49942.9 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367695
telemt_connections_bad_total 44563
telemt_handshake_timeouts_total 10642
telemt_upstream_connect_attempt_total 19155
telemt_upstream_connect_success_total 18978
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 19155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 27909
telemt_me_reconnect_success_total 16314
telemt_me_reader_eof_total 17250
telemt_me_idle_close_by_peer_total 17250
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 92296
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277154
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 993
telemt_desync_full_logged_total 312
telemt_desync_suppressed_total 681
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 409
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 29
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 16867
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 16285
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 553
telemt_user_connections_total{user="hello"} 277092
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 21393997553 (19.92 GB)
telemt_user_octets_to_client{user="hello"} 227492541238 (211.87 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 43
```