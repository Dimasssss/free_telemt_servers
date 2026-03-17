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

# Server Metrics 2026-03-17 17:43:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 82675.1 (22h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 997249
telemt_connections_bad_total 6537
telemt_handshake_timeouts_total 27896
telemt_upstream_connect_attempt_total 19513
telemt_upstream_connect_success_total 19034
telemt_upstream_connect_fail_total 479
telemt_upstream_connect_attempts_per_request{bucket="1"} 19513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8945
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 479
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 29717
telemt_me_reconnect_success_total 12601
telemt_me_reader_eof_total 13729
telemt_me_idle_close_by_peer_total 13728
telemt_me_route_drop_no_conn_total 455425
telemt_me_route_drop_channel_closed_total 125
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 912370
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6060
telemt_desync_full_logged_total 1720
telemt_desync_suppressed_total 4340
telemt_desync_frames_bucket_total{bucket="1_2"} 1675
telemt_desync_frames_bucket_total{bucket="3_10"} 2327
telemt_desync_frames_bucket_total{bucket="gt_10"} 2058
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 13312
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12579
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 711
telemt_user_connections_total{user="hello"} 906625
telemt_user_connections_current{user="hello"} 1062
telemt_user_octets_from_client{user="hello"} 13880260887 (12.93 GB)
telemt_user_octets_to_client{user="hello"} 310641441939 (289.31 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 359
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 82926.8 (23h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 864604
telemt_connections_bad_total 50933
telemt_handshake_timeouts_total 31863
telemt_upstream_connect_attempt_total 344789
telemt_upstream_connect_success_total 344023
telemt_upstream_connect_fail_total 766
telemt_upstream_connect_attempts_per_request{bucket="1"} 344789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 285649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25435
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32937
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 766
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 51274
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15296
telemt_me_idle_close_by_peer_total 15296
telemt_me_route_drop_no_conn_total 235904
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 416215
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1553
telemt_desync_full_logged_total 493
telemt_desync_suppressed_total 1060
telemt_desync_frames_bucket_total{bucket="1_2"} 353
telemt_desync_frames_bucket_total{bucket="3_10"} 676
telemt_desync_frames_bucket_total{bucket="gt_10"} 524
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14906
telemt_me_refill_failed_total 1174
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1341
telemt_user_connections_total{user="hello"} 742389
telemt_user_connections_current{user="hello"} 1729
telemt_user_octets_from_client{user="hello"} 9988608807 (9.30 GB)
telemt_user_octets_to_client{user="hello"} 200263590194 (186.51 GB)
telemt_user_msgs_from_client{user="hello"} 5556148
telemt_user_msgs_to_client{user="hello"} 23190682
telemt_user_unique_ips_current{user="hello"} 381
telemt_user_unique_ips_recent_window{user="hello"} 428
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 82702.5 (22h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 444096
telemt_connections_bad_total 14047
telemt_handshake_timeouts_total 20649
telemt_upstream_connect_attempt_total 20649
telemt_upstream_connect_success_total 20531
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 20649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11118
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 37011
telemt_me_reconnect_success_total 16343
telemt_me_reader_eof_total 17881
telemt_me_idle_close_by_peer_total 17874
telemt_me_route_drop_no_conn_total 211389
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 387651
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1098
telemt_desync_full_logged_total 331
telemt_desync_suppressed_total 767
telemt_desync_frames_bucket_total{bucket="1_2"} 363
telemt_desync_frames_bucket_total{bucket="3_10"} 478
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 17209
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16331
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 866
telemt_user_connections_total{user="hello"} 385803
telemt_user_connections_current{user="hello"} 1390
telemt_user_octets_from_client{user="hello"} 25153680376 (23.43 GB)
telemt_user_octets_to_client{user="hello"} 137616217356 (128.17 GB)
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 82761.9 (22h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 916051
telemt_connections_bad_total 21046
telemt_handshake_timeouts_total 17870
telemt_upstream_connect_attempt_total 80414
telemt_upstream_connect_success_total 80018
telemt_upstream_connect_fail_total 396
telemt_upstream_connect_attempts_per_request{bucket="1"} 80414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10896
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 330
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 396
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 32803
telemt_me_reconnect_success_total 12503
telemt_me_reader_eof_total 13811
telemt_me_idle_close_by_peer_total 13810
telemt_me_route_drop_no_conn_total 388336
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 733046
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2363
telemt_desync_full_logged_total 758
telemt_desync_suppressed_total 1605
telemt_desync_frames_bucket_total{bucket="1_2"} 570
telemt_desync_frames_bucket_total{bucket="3_10"} 1053
telemt_desync_frames_bucket_total{bucket="gt_10"} 740
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 13364
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12494
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 861
telemt_user_connections_total{user="hello"} 796149
telemt_user_connections_current{user="hello"} 1764
telemt_user_octets_from_client{user="hello"} 9677780787 (9.01 GB)
telemt_user_octets_to_client{user="hello"} 263448050473 (245.36 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 82733.9 (22h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 488872
telemt_connections_bad_total 71795
telemt_handshake_timeouts_total 4499
telemt_upstream_connect_attempt_total 38812
telemt_upstream_connect_success_total 38311
telemt_upstream_connect_fail_total 501
telemt_upstream_connect_attempts_per_request{bucket="1"} 38812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12852
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 501
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50156
telemt_me_reconnect_success_total 17677
telemt_me_reader_eof_total 19302
telemt_me_idle_close_by_peer_total 19300
telemt_me_route_drop_no_conn_total 143690
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370816
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1640
telemt_desync_full_logged_total 406
telemt_desync_suppressed_total 1234
telemt_desync_frames_bucket_total{bucket="1_2"} 665
telemt_desync_frames_bucket_total{bucket="3_10"} 652
telemt_desync_frames_bucket_total{bucket="gt_10"} 323
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18987
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 17669
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1310
telemt_user_connections_total{user="hello"} 387517
telemt_user_connections_current{user="hello"} 1722
telemt_user_octets_from_client{user="hello"} 6601868632 (6.15 GB)
telemt_user_octets_to_client{user="hello"} 175637925292 (163.58 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 444
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 82895.8 (23h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 841588
telemt_connections_bad_total 60505
telemt_handshake_timeouts_total 8017
telemt_upstream_connect_attempt_total 16650
telemt_upstream_connect_success_total 16558
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 16650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8554
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 23642
telemt_me_reconnect_success_total 12372
telemt_me_reader_eof_total 13464
telemt_me_idle_close_by_peer_total 13462
telemt_me_route_drop_no_conn_total 625128
telemt_me_route_drop_channel_closed_total 77
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 865386
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1556
telemt_desync_full_logged_total 536
telemt_desync_suppressed_total 1020
telemt_desync_frames_bucket_total{bucket="1_2"} 375
telemt_desync_frames_bucket_total{bucket="3_10"} 602
telemt_desync_frames_bucket_total{bucket="gt_10"} 579
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 12934
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12358
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 562
telemt_user_connections_total{user="hello"} 728450
telemt_user_connections_current{user="hello"} 919
telemt_user_octets_from_client{user="hello"} 11075888036 (10.32 GB)
telemt_user_octets_to_client{user="hello"} 319573366300 (297.63 GB)
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 30662.1 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140303
telemt_connections_bad_total 17094
telemt_handshake_timeouts_total 4609
telemt_upstream_connect_attempt_total 14433
telemt_upstream_connect_success_total 14307
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 14433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24172
telemt_me_reconnect_success_total 12595
telemt_me_reader_eof_total 13338
telemt_me_idle_close_by_peer_total 13338
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 33302
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111009
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 169
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 13107
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12572
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 110974
telemt_user_connections_current{user="hello"} 1043
telemt_user_octets_from_client{user="hello"} 7032744789 (6.55 GB)
telemt_user_octets_to_client{user="hello"} 110082792594 (102.52 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 119
```