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

# Server Metrics 2026-03-17 19:20:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 88485.1 (24h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1090422
telemt_connections_bad_total 7836
telemt_handshake_timeouts_total 29954
telemt_upstream_connect_attempt_total 20521
telemt_upstream_connect_success_total 20033
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 20521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9409
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 30413
telemt_me_reconnect_success_total 13286
telemt_me_reader_eof_total 14455
telemt_me_idle_close_by_peer_total 14454
telemt_me_route_drop_no_conn_total 493005
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 998255
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6577
telemt_desync_full_logged_total 1874
telemt_desync_suppressed_total 4703
telemt_desync_frames_bucket_total{bucket="1_2"} 1788
telemt_desync_frames_bucket_total{bucket="3_10"} 2516
telemt_desync_frames_bucket_total{bucket="gt_10"} 2273
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 14015
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13264
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 729
telemt_user_connections_total{user="hello"} 992502
telemt_user_connections_current{user="hello"} 967
telemt_user_octets_from_client{user="hello"} 15056533859 (14.02 GB)
telemt_user_octets_to_client{user="hello"} 345952941171 (322.19 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 88736.7 (24h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1070607
telemt_connections_bad_total 56272
telemt_handshake_timeouts_total 36813
telemt_upstream_connect_attempt_total 456131
telemt_upstream_connect_success_total 455262
telemt_upstream_connect_fail_total 869
telemt_upstream_connect_attempts_per_request{bucket="1"} 456131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29815
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 869
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 56964
telemt_me_reconnect_success_total 13815
telemt_me_reader_eof_total 15726
telemt_me_idle_close_by_peer_total 15726
telemt_me_route_drop_no_conn_total 262760
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482073
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1883
telemt_desync_full_logged_total 605
telemt_desync_suppressed_total 1278
telemt_desync_frames_bucket_total{bucket="1_2"} 421
telemt_desync_frames_bucket_total{bucket="3_10"} 788
telemt_desync_frames_bucket_total{bucket="gt_10"} 674
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 15328
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 13799
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1513
telemt_user_connections_total{user="hello"} 918515
telemt_user_connections_current{user="hello"} 1634
telemt_user_octets_from_client{user="hello"} 12694369890 (11.82 GB)
telemt_user_octets_to_client{user="hello"} 269160032010 (250.67 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 459
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 88512.7 (24h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 558723
telemt_connections_bad_total 19564
telemt_handshake_timeouts_total 21757
telemt_upstream_connect_attempt_total 21647
telemt_upstream_connect_success_total 21524
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 21647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11629
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 37700
telemt_me_reconnect_success_total 17029
telemt_me_reader_eof_total 18616
telemt_me_idle_close_by_peer_total 18609
telemt_me_route_drop_no_conn_total 251124
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 490035
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1392
telemt_desync_full_logged_total 409
telemt_desync_suppressed_total 983
telemt_desync_frames_bucket_total{bucket="1_2"} 416
telemt_desync_frames_bucket_total{bucket="3_10"} 573
telemt_desync_frames_bucket_total{bucket="gt_10"} 403
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 17904
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17017
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 875
telemt_user_connections_total{user="hello"} 488275
telemt_user_connections_current{user="hello"} 1142
telemt_user_octets_from_client{user="hello"} 27261727116 (25.39 GB)
telemt_user_octets_to_client{user="hello"} 188610321176 (175.66 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 88572.0 (24h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1055654
telemt_connections_bad_total 26505
telemt_handshake_timeouts_total 20238
telemt_upstream_connect_attempt_total 81307
telemt_upstream_connect_success_total 80904
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 81307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11335
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33387
telemt_me_reconnect_success_total 13084
telemt_me_reader_eof_total 14438
telemt_me_idle_close_by_peer_total 14437
telemt_me_route_drop_no_conn_total 437689
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 854114
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2808
telemt_desync_full_logged_total 910
telemt_desync_suppressed_total 1898
telemt_desync_frames_bucket_total{bucket="1_2"} 673
telemt_desync_frames_bucket_total{bucket="3_10"} 1223
telemt_desync_frames_bucket_total{bucket="gt_10"} 912
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 13959
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13075
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 875
telemt_user_connections_total{user="hello"} 917178
telemt_user_connections_current{user="hello"} 1511
telemt_user_octets_from_client{user="hello"} 13015647703 (12.12 GB)
telemt_user_octets_to_client{user="hello"} 345496335537 (321.77 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 404
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 88543.7 (24h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 614515
telemt_connections_bad_total 75921
telemt_handshake_timeouts_total 5262
telemt_upstream_connect_attempt_total 39962
telemt_upstream_connect_success_total 39431
telemt_upstream_connect_fail_total 531
telemt_upstream_connect_attempts_per_request{bucket="1"} 39962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13416
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 531
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50974
telemt_me_reconnect_success_total 18492
telemt_me_reader_eof_total 20166
telemt_me_idle_close_by_peer_total 20164
telemt_me_route_drop_no_conn_total 189617
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482246
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2175
telemt_desync_full_logged_total 580
telemt_desync_suppressed_total 1595
telemt_desync_frames_bucket_total{bucket="1_2"} 781
telemt_desync_frames_bucket_total{bucket="3_10"} 853
telemt_desync_frames_bucket_total{bucket="gt_10"} 541
telemt_pool_swap_total 43
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19822
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18484
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1330
telemt_user_connections_total{user="hello"} 498900
telemt_user_connections_current{user="hello"} 1300
telemt_user_octets_from_client{user="hello"} 9863751684 (9.19 GB)
telemt_user_octets_to_client{user="hello"} 233053653268 (217.05 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 396
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 88705.5 (24h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 907890
telemt_connections_bad_total 61513
telemt_handshake_timeouts_total 8890
telemt_upstream_connect_attempt_total 17652
telemt_upstream_connect_success_total 17553
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 17652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9081
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 24377
telemt_me_reconnect_success_total 13103
telemt_me_reader_eof_total 14247
telemt_me_idle_close_by_peer_total 14245
telemt_me_route_drop_no_conn_total 654242
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 923657
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1807
telemt_desync_full_logged_total 624
telemt_desync_suppressed_total 1183
telemt_desync_frames_bucket_total{bucket="1_2"} 436
telemt_desync_frames_bucket_total{bucket="3_10"} 692
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 73
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13677
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13089
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 574
telemt_user_connections_total{user="hello"} 786698
telemt_user_connections_current{user="hello"} 828
telemt_user_octets_from_client{user="hello"} 12079948360 (11.25 GB)
telemt_user_octets_to_client{user="hello"} 340301203816 (316.93 GB)
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 36472.0 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236512
telemt_connections_bad_total 30525
telemt_handshake_timeouts_total 6176
telemt_upstream_connect_attempt_total 15892
telemt_upstream_connect_success_total 15754
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 15892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 25330
telemt_me_reconnect_success_total 13743
telemt_me_reader_eof_total 14531
telemt_me_idle_close_by_peer_total 14531
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 56588
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181936
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
telemt_me_writer_removed_unexpected_total 14270
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 13718
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 527
telemt_user_connections_total{user="hello"} 181875
telemt_user_connections_current{user="hello"} 790
telemt_user_octets_from_client{user="hello"} 17421339721 (16.22 GB)
telemt_user_octets_to_client{user="hello"} 155136167638 (144.48 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 80
```