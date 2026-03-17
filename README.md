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

# Server Metrics 2026-03-17 20:46:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 93683.3 (26h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1157121
telemt_connections_bad_total 8633
telemt_handshake_timeouts_total 30516
telemt_upstream_connect_attempt_total 21373
telemt_upstream_connect_success_total 20882
telemt_upstream_connect_fail_total 490
telemt_upstream_connect_attempts_per_request{bucket="1"} 21372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 490
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31013
telemt_me_reconnect_success_total 13882
telemt_me_reader_eof_total 15092
telemt_me_idle_close_by_peer_total 15091
telemt_me_route_drop_no_conn_total 517890
telemt_me_route_drop_channel_closed_total 153
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1060726
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7078
telemt_desync_full_logged_total 2028
telemt_desync_suppressed_total 5050
telemt_desync_frames_bucket_total{bucket="1_2"} 1910
telemt_desync_frames_bucket_total{bucket="3_10"} 2685
telemt_desync_frames_bucket_total{bucket="gt_10"} 2483
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 14624
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13860
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 742
telemt_user_connections_total{user="hello"} 1054961
telemt_user_connections_current{user="hello"} 600
telemt_user_octets_from_client{user="hello"} 18916013635 (17.62 GB)
telemt_user_octets_to_client{user="hello"} 370137977107 (344.72 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 93935.0 (26h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1188581
telemt_connections_bad_total 59430
telemt_handshake_timeouts_total 42650
telemt_upstream_connect_attempt_total 456929
telemt_upstream_connect_success_total 456045
telemt_upstream_connect_fail_total 884
telemt_upstream_connect_attempts_per_request{bucket="1"} 456929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 884
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57486
telemt_me_reconnect_success_total 14333
telemt_me_reader_eof_total 16287
telemt_me_idle_close_by_peer_total 16287
telemt_me_route_drop_no_conn_total 299561
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 587283
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2556
telemt_desync_full_logged_total 822
telemt_desync_suppressed_total 1734
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 1066
telemt_desync_frames_bucket_total{bucket="gt_10"} 997
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 15859
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14317
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1526
telemt_user_connections_total{user="hello"} 1023710
telemt_user_connections_current{user="hello"} 1320
telemt_user_octets_from_client{user="hello"} 14200697114 (13.23 GB)
telemt_user_octets_to_client{user="hello"} 335216128050 (312.19 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 93711.1 (26h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 657838
telemt_connections_bad_total 37585
telemt_handshake_timeouts_total 22337
telemt_upstream_connect_attempt_total 22547
telemt_upstream_connect_success_total 22417
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 22547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12075
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38333
telemt_me_reconnect_success_total 17659
telemt_me_reader_eof_total 19277
telemt_me_idle_close_by_peer_total 19270
telemt_me_route_drop_no_conn_total 281611
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 567100
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1794
telemt_desync_full_logged_total 535
telemt_desync_suppressed_total 1259
telemt_desync_frames_bucket_total{bucket="1_2"} 507
telemt_desync_frames_bucket_total{bucket="3_10"} 708
telemt_desync_frames_bucket_total{bucket="gt_10"} 579
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 18546
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17647
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 887
telemt_user_connections_total{user="hello"} 565372
telemt_user_connections_current{user="hello"} 986
telemt_user_octets_from_client{user="hello"} 28510996628 (26.55 GB)
telemt_user_octets_to_client{user="hello"} 234147190688 (218.07 GB)
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 93770.3 (26h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1160257
telemt_connections_bad_total 34591
telemt_handshake_timeouts_total 21148
telemt_upstream_connect_attempt_total 82119
telemt_upstream_connect_success_total 81707
telemt_upstream_connect_fail_total 412
telemt_upstream_connect_attempts_per_request{bucket="1"} 82119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11740
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 339
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 412
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33934
telemt_me_reconnect_success_total 13622
telemt_me_reader_eof_total 15018
telemt_me_idle_close_by_peer_total 15017
telemt_me_route_drop_no_conn_total 484512
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 946087
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3251
telemt_desync_full_logged_total 1035
telemt_desync_suppressed_total 2216
telemt_desync_frames_bucket_total{bucket="1_2"} 796
telemt_desync_frames_bucket_total{bucket="3_10"} 1379
telemt_desync_frames_bucket_total{bucket="gt_10"} 1076
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 14509
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13613
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 887
telemt_user_connections_total{user="hello"} 1008606
telemt_user_connections_current{user="hello"} 1214
telemt_user_octets_from_client{user="hello"} 15037668907 (14.00 GB)
telemt_user_octets_to_client{user="hello"} 415071970349 (386.57 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 93742.4 (26h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 715762
telemt_connections_bad_total 89889
telemt_handshake_timeouts_total 6075
telemt_upstream_connect_attempt_total 40942
telemt_upstream_connect_success_total 40395
telemt_upstream_connect_fail_total 547
telemt_upstream_connect_attempts_per_request{bucket="1"} 40942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13946
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 392
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 547
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51679
telemt_me_reconnect_success_total 19193
telemt_me_reader_eof_total 20903
telemt_me_idle_close_by_peer_total 20901
telemt_me_route_drop_no_conn_total 222742
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 564730
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2602
telemt_desync_full_logged_total 748
telemt_desync_suppressed_total 1854
telemt_desync_frames_bucket_total{bucket="1_2"} 873
telemt_desync_frames_bucket_total{bucket="3_10"} 1041
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 47
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20537
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 19185
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1344
telemt_user_connections_total{user="hello"} 581356
telemt_user_connections_current{user="hello"} 1076
telemt_user_octets_from_client{user="hello"} 11424395160 (10.64 GB)
telemt_user_octets_to_client{user="hello"} 277466806676 (258.41 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 93903.5 (26h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 966263
telemt_connections_bad_total 68720
telemt_handshake_timeouts_total 9174
telemt_upstream_connect_attempt_total 18598
telemt_upstream_connect_success_total 18489
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 18598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9576
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25054
telemt_me_reconnect_success_total 13778
telemt_me_reader_eof_total 14972
telemt_me_idle_close_by_peer_total 14970
telemt_me_route_drop_no_conn_total 676138
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 967518
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1933
telemt_desync_full_logged_total 678
telemt_desync_suppressed_total 1255
telemt_desync_frames_bucket_total{bucket="1_2"} 446
telemt_desync_frames_bucket_total{bucket="3_10"} 734
telemt_desync_frames_bucket_total{bucket="gt_10"} 753
telemt_pool_swap_total 79
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14359
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13764
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 581
telemt_user_connections_total{user="hello"} 830552
telemt_user_connections_current{user="hello"} 598
telemt_user_octets_from_client{user="hello"} 12896772184 (12.01 GB)
telemt_user_octets_to_client{user="hello"} 359055858180 (334.40 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 41670.5 (11h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297216
telemt_connections_bad_total 39280
telemt_handshake_timeouts_total 8668
telemt_upstream_connect_attempt_total 17242
telemt_upstream_connect_success_total 17082
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 17242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26401
telemt_me_reconnect_success_total 14810
telemt_me_reader_eof_total 15652
telemt_me_idle_close_by_peer_total 15652
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 73055
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 228922
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 689
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 501
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 20
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15347
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 14782
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 228869
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 20556455745 (19.14 GB)
telemt_user_octets_to_client{user="hello"} 190042362830 (176.99 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 68
```