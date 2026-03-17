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

# Server Metrics 2026-03-17 17:58:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 83595.0 (23h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1012219
telemt_connections_bad_total 6677
telemt_handshake_timeouts_total 27984
telemt_upstream_connect_attempt_total 19652
telemt_upstream_connect_success_total 19172
telemt_upstream_connect_fail_total 480
telemt_upstream_connect_attempts_per_request{bucket="1"} 19652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 480
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 29812
telemt_me_reconnect_success_total 12694
telemt_me_reader_eof_total 13829
telemt_me_idle_close_by_peer_total 13828
telemt_me_route_drop_no_conn_total 462121
telemt_me_route_drop_channel_closed_total 126
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 926514
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6165
telemt_desync_full_logged_total 1745
telemt_desync_suppressed_total 4420
telemt_desync_frames_bucket_total{bucket="1_2"} 1690
telemt_desync_frames_bucket_total{bucket="3_10"} 2376
telemt_desync_frames_bucket_total{bucket="gt_10"} 2099
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13409
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12672
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 715
telemt_user_connections_total{user="hello"} 920767
telemt_user_connections_current{user="hello"} 1102
telemt_user_octets_from_client{user="hello"} 14071248627 (13.10 GB)
telemt_user_octets_to_client{user="hello"} 317588369507 (295.78 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 369
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 83847.1 (23h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 904054
telemt_connections_bad_total 52445
telemt_handshake_timeouts_total 32427
telemt_upstream_connect_attempt_total 372588
telemt_upstream_connect_success_total 371794
telemt_upstream_connect_fail_total 794
telemt_upstream_connect_attempts_per_request{bucket="1"} 372588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 309722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26507
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35563
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 794
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 52842
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15345
telemt_me_idle_close_by_peer_total 15345
telemt_me_route_drop_no_conn_total 238323
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 421289
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1570
telemt_desync_full_logged_total 500
telemt_desync_suppressed_total 1070
telemt_desync_frames_bucket_total{bucket="1_2"} 360
telemt_desync_frames_bucket_total{bucket="3_10"} 684
telemt_desync_frames_bucket_total{bucket="gt_10"} 526
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14955
telemt_me_refill_failed_total 1223
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1390
telemt_user_connections_total{user="hello"} 775189
telemt_user_connections_current{user="hello"} 1560
telemt_user_octets_from_client{user="hello"} 10514558839 (9.79 GB)
telemt_user_octets_to_client{user="hello"} 208681422900 (194.35 GB)
telemt_user_msgs_from_client{user="hello"} 6055228
telemt_user_msgs_to_client{user="hello"} 25553470
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 83622.4 (23h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465753
telemt_connections_bad_total 16032
telemt_handshake_timeouts_total 20835
telemt_upstream_connect_attempt_total 20803
telemt_upstream_connect_success_total 20685
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 20803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11202
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 37121
telemt_me_reconnect_success_total 16453
telemt_me_reader_eof_total 17996
telemt_me_idle_close_by_peer_total 17989
telemt_me_route_drop_no_conn_total 217910
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 405959
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1147
telemt_desync_full_logged_total 347
telemt_desync_suppressed_total 800
telemt_desync_frames_bucket_total{bucket="1_2"} 373
telemt_desync_frames_bucket_total{bucket="3_10"} 498
telemt_desync_frames_bucket_total{bucket="gt_10"} 276
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 17320
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16441
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 867
telemt_user_connections_total{user="hello"} 404161
telemt_user_connections_current{user="hello"} 1344
telemt_user_octets_from_client{user="hello"} 25987921560 (24.20 GB)
telemt_user_octets_to_client{user="hello"} 145293023964 (135.31 GB)
telemt_user_unique_ips_current{user="hello"} 366
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 83681.8 (23h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 939768
telemt_connections_bad_total 22166
telemt_handshake_timeouts_total 18333
telemt_upstream_connect_attempt_total 80548
telemt_upstream_connect_success_total 80151
telemt_upstream_connect_fail_total 397
telemt_upstream_connect_attempts_per_request{bucket="1"} 80548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 333
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 397
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 32893
telemt_me_reconnect_success_total 12593
telemt_me_reader_eof_total 13905
telemt_me_idle_close_by_peer_total 13904
telemt_me_route_drop_no_conn_total 397112
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 754207
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2412
telemt_desync_full_logged_total 772
telemt_desync_suppressed_total 1640
telemt_desync_frames_bucket_total{bucket="1_2"} 588
telemt_desync_frames_bucket_total{bucket="3_10"} 1073
telemt_desync_frames_bucket_total{bucket="gt_10"} 751
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 13454
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12584
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 861
telemt_user_connections_total{user="hello"} 817306
telemt_user_connections_current{user="hello"} 1748
telemt_user_octets_from_client{user="hello"} 10028194959 (9.34 GB)
telemt_user_octets_to_client{user="hello"} 277735428905 (258.66 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 451
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 83653.7 (23h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 516802
telemt_connections_bad_total 73609
telemt_handshake_timeouts_total 4562
telemt_upstream_connect_attempt_total 38948
telemt_upstream_connect_success_total 38443
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 38948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50245
telemt_me_reconnect_success_total 17766
telemt_me_reader_eof_total 19396
telemt_me_idle_close_by_peer_total 19394
telemt_me_route_drop_no_conn_total 152154
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 391473
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1760
telemt_desync_full_logged_total 441
telemt_desync_suppressed_total 1319
telemt_desync_frames_bucket_total{bucket="1_2"} 702
telemt_desync_frames_bucket_total{bucket="3_10"} 697
telemt_desync_frames_bucket_total{bucket="gt_10"} 361
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19077
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 17758
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1311
telemt_user_connections_total{user="hello"} 408161
telemt_user_connections_current{user="hello"} 1570
telemt_user_octets_from_client{user="hello"} 7291530556 (6.79 GB)
telemt_user_octets_to_client{user="hello"} 186831201684 (174.00 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 422
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 83815.5 (23h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 853130
telemt_connections_bad_total 60827
telemt_handshake_timeouts_total 8110
telemt_upstream_connect_attempt_total 16805
telemt_upstream_connect_success_total 16712
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 16805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8649
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 23752
telemt_me_reconnect_success_total 12482
telemt_me_reader_eof_total 13582
telemt_me_idle_close_by_peer_total 13580
telemt_me_route_drop_no_conn_total 630316
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 875384
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1585
telemt_desync_full_logged_total 544
telemt_desync_suppressed_total 1041
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 617
telemt_desync_frames_bucket_total{bucket="gt_10"} 585
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 13046
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12468
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 564
telemt_user_connections_total{user="hello"} 738444
telemt_user_connections_current{user="hello"} 886
telemt_user_octets_from_client{user="hello"} 11238448132 (10.47 GB)
telemt_user_octets_to_client{user="hello"} 322838794020 (300.67 GB)
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 31582.0 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155347
telemt_connections_bad_total 18284
telemt_handshake_timeouts_total 5005
telemt_upstream_connect_attempt_total 14689
telemt_upstream_connect_success_total 14561
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 14688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6665
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24366
telemt_me_reconnect_success_total 12788
telemt_me_reader_eof_total 13533
telemt_me_idle_close_by_peer_total 13533
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 37139
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123146
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 232
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 163
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 13302
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12765
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 123101
telemt_user_connections_current{user="hello"} 1022
telemt_user_octets_from_client{user="hello"} 10335433225 (9.63 GB)
telemt_user_octets_to_client{user="hello"} 118125674578 (110.01 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 105
```