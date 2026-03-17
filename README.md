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

# Server Metrics 2026-03-17 18:34:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 85734.8 (23h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1045219
telemt_connections_bad_total 7425
telemt_handshake_timeouts_total 28219
telemt_upstream_connect_attempt_total 20018
telemt_upstream_connect_success_total 19536
telemt_upstream_connect_fail_total 482
telemt_upstream_connect_attempts_per_request{bucket="1"} 20018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 482
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 30047
telemt_me_reconnect_success_total 12927
telemt_me_reader_eof_total 14080
telemt_me_idle_close_by_peer_total 14079
telemt_me_route_drop_no_conn_total 476058
telemt_me_route_drop_channel_closed_total 139
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 956935
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6308
telemt_desync_full_logged_total 1795
telemt_desync_suppressed_total 4513
telemt_desync_frames_bucket_total{bucket="1_2"} 1739
telemt_desync_frames_bucket_total{bucket="3_10"} 2424
telemt_desync_frames_bucket_total{bucket="gt_10"} 2145
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13648
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12905
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 721
telemt_user_connections_total{user="hello"} 951175
telemt_user_connections_current{user="hello"} 1072
telemt_user_octets_from_client{user="hello"} 14474961059 (13.48 GB)
telemt_user_octets_to_client{user="hello"} 332237921535 (309.42 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 85986.0 (23h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 994699
telemt_connections_bad_total 55822
telemt_handshake_timeouts_total 33951
telemt_upstream_connect_attempt_total 440865
telemt_upstream_connect_success_total 440006
telemt_upstream_connect_fail_total 859
telemt_upstream_connect_attempts_per_request{bucket="1"} 440865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 367733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29034
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 859
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 56714
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15463
telemt_me_idle_close_by_peer_total 15463
telemt_me_route_drop_no_conn_total 243002
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429277
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1582
telemt_desync_full_logged_total 505
telemt_desync_suppressed_total 1077
telemt_desync_frames_bucket_total{bucket="1_2"} 361
telemt_desync_frames_bucket_total{bucket="3_10"} 690
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 15076
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1511
telemt_user_connections_total{user="hello"} 851302
telemt_user_connections_current{user="hello"} 1817
telemt_user_octets_from_client{user="hello"} 11407634103 (10.62 GB)
telemt_user_octets_to_client{user="hello"} 223531164155 (208.18 GB)
telemt_user_msgs_from_client{user="hello"} 7111619
telemt_user_msgs_to_client{user="hello"} 30015375
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 85762.1 (23h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 510089
telemt_connections_bad_total 19012
telemt_handshake_timeouts_total 21217
telemt_upstream_connect_attempt_total 21196
telemt_upstream_connect_success_total 21078
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 21196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11395
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 37383
telemt_me_reconnect_success_total 16714
telemt_me_reader_eof_total 18279
telemt_me_idle_close_by_peer_total 18272
telemt_me_route_drop_no_conn_total 233487
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 444830
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1239
telemt_desync_full_logged_total 371
telemt_desync_suppressed_total 868
telemt_desync_frames_bucket_total{bucket="1_2"} 390
telemt_desync_frames_bucket_total{bucket="3_10"} 524
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 17585
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16702
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 871
telemt_user_connections_total{user="hello"} 443029
telemt_user_connections_current{user="hello"} 1191
telemt_user_octets_from_client{user="hello"} 26589963992 (24.76 GB)
telemt_user_octets_to_client{user="hello"} 163649376900 (152.41 GB)
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 85821.6 (23h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 992447
telemt_connections_bad_total 23650
telemt_handshake_timeouts_total 19406
telemt_upstream_connect_attempt_total 80909
telemt_upstream_connect_success_total 80507
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 80909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11129
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33120
telemt_me_reconnect_success_total 12818
telemt_me_reader_eof_total 14152
telemt_me_idle_close_by_peer_total 14151
telemt_me_route_drop_no_conn_total 415782
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 800070
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2545
telemt_desync_full_logged_total 823
telemt_desync_suppressed_total 1722
telemt_desync_frames_bucket_total{bucket="1_2"} 617
telemt_desync_frames_bucket_total{bucket="3_10"} 1119
telemt_desync_frames_bucket_total{bucket="gt_10"} 809
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 13686
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12809
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 868
telemt_user_connections_total{user="hello"} 863146
telemt_user_connections_current{user="hello"} 1605
telemt_user_octets_from_client{user="hello"} 11103686747 (10.34 GB)
telemt_user_octets_to_client{user="hello"} 309734686529 (288.46 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 427
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 85793.3 (23h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 565715
telemt_connections_bad_total 75350
telemt_handshake_timeouts_total 5060
telemt_upstream_connect_attempt_total 39490
telemt_upstream_connect_success_total 38968
telemt_upstream_connect_fail_total 522
telemt_upstream_connect_attempts_per_request{bucket="1"} 39490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 522
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50640
telemt_me_reconnect_success_total 18159
telemt_me_reader_eof_total 19808
telemt_me_idle_close_by_peer_total 19806
telemt_me_route_drop_no_conn_total 170105
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 436139
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1951
telemt_desync_full_logged_total 500
telemt_desync_suppressed_total 1451
telemt_desync_frames_bucket_total{bucket="1_2"} 734
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 456
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19482
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18151
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1323
telemt_user_connections_total{user="hello"} 452812
telemt_user_connections_current{user="hello"} 1492
telemt_user_octets_from_client{user="hello"} 8185300296 (7.62 GB)
telemt_user_octets_to_client{user="hello"} 208250115480 (193.95 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 85955.1 (23h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 878899
telemt_connections_bad_total 61426
telemt_handshake_timeouts_total 8572
telemt_upstream_connect_attempt_total 17182
telemt_upstream_connect_success_total 17087
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 17182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 24042
telemt_me_reconnect_success_total 12771
telemt_me_reader_eof_total 13894
telemt_me_idle_close_by_peer_total 13892
telemt_me_route_drop_no_conn_total 641764
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 897275
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1700
telemt_desync_full_logged_total 581
telemt_desync_suppressed_total 1119
telemt_desync_frames_bucket_total{bucket="1_2"} 409
telemt_desync_frames_bucket_total{bucket="3_10"} 654
telemt_desync_frames_bucket_total{bucket="gt_10"} 637
telemt_pool_swap_total 70
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13339
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12757
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 760328
telemt_user_connections_current{user="hello"} 802
telemt_user_octets_from_client{user="hello"} 11494601952 (10.71 GB)
telemt_user_octets_to_client{user="hello"} 329661680428 (307.02 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 33721.5 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189015
telemt_connections_bad_total 20350
telemt_handshake_timeouts_total 5568
telemt_upstream_connect_attempt_total 15208
telemt_upstream_connect_success_total 15076
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 15208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24783
telemt_me_reconnect_success_total 13203
telemt_me_reader_eof_total 13976
telemt_me_idle_close_by_peer_total 13976
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 45894
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150624
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 346
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 244
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 117
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 13719
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 13179
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 516
telemt_user_connections_total{user="hello"} 150575
telemt_user_connections_current{user="hello"} 920
telemt_user_octets_from_client{user="hello"} 12535351341 (11.67 GB)
telemt_user_octets_to_client{user="hello"} 136445895554 (127.08 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 98
```