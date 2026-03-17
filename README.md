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

# Server Metrics 2026-03-17 14:24:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 70724.3 (19h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 744721
telemt_connections_bad_total 5709
telemt_handshake_timeouts_total 21935
telemt_upstream_connect_attempt_total 17206
telemt_upstream_connect_success_total 16749
telemt_upstream_connect_fail_total 457
telemt_upstream_connect_attempts_per_request{bucket="1"} 17206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 457
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 21473
telemt_me_reconnect_success_total 10908
telemt_me_reader_eof_total 11791
telemt_me_idle_close_by_peer_total 11790
telemt_me_route_drop_no_conn_total 295853
telemt_me_route_drop_channel_closed_total 75
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 675229
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4650
telemt_desync_full_logged_total 1316
telemt_desync_suppressed_total 3334
telemt_desync_frames_bucket_total{bucket="1_2"} 1300
telemt_desync_frames_bucket_total{bucket="3_10"} 1901
telemt_desync_frames_bucket_total{bucket="gt_10"} 1449
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11391
telemt_me_refill_failed_total 325
telemt_me_writer_restored_same_endpoint_total 10886
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 483
telemt_user_connections_total{user="hello"} 677107
telemt_user_connections_current{user="hello"} 1020
telemt_user_octets_from_client{user="hello"} 11291595683 (10.52 GB)
telemt_user_octets_to_client{user="hello"} 227939651287 (212.29 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 347
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 70975.7 (19h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 467727
telemt_connections_bad_total 29912
telemt_handshake_timeouts_total 23400
telemt_upstream_connect_attempt_total 49072
telemt_upstream_connect_success_total 48649
telemt_upstream_connect_fail_total 422
telemt_upstream_connect_attempts_per_request{bucket="1"} 49071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10659
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3709
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 422
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 33121
telemt_me_reconnect_success_total 13371
telemt_me_reader_eof_total 14548
telemt_me_idle_close_by_peer_total 14548
telemt_me_route_drop_no_conn_total 188290
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360021
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1437
telemt_desync_full_logged_total 452
telemt_desync_suppressed_total 985
telemt_desync_frames_bucket_total{bucket="1_2"} 321
telemt_desync_frames_bucket_total{bucket="3_10"} 627
telemt_desync_frames_bucket_total{bucket="gt_10"} 489
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14151
telemt_me_refill_failed_total 613
telemt_me_writer_restored_same_endpoint_total 13355
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 780
telemt_user_connections_total{user="hello"} 391652
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 4265885230 (3.97 GB)
telemt_user_octets_to_client{user="hello"} 122468963633 (114.06 GB)
telemt_user_msgs_from_client{user="hello"} 462100
telemt_user_msgs_to_client{user="hello"} 1459053
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 70751.6 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244155
telemt_connections_bad_total 7813
telemt_handshake_timeouts_total 16990
telemt_upstream_connect_attempt_total 18682
telemt_upstream_connect_success_total 18587
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 18682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10204
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 23314
telemt_me_reconnect_success_total 14999
telemt_me_reader_eof_total 16128
telemt_me_idle_close_by_peer_total 16125
telemt_me_route_drop_no_conn_total 102192
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206646
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 763
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 543
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 15466
telemt_me_refill_failed_total 257
telemt_me_writer_restored_same_endpoint_total 14988
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 467
telemt_user_connections_total{user="hello"} 206517
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 15842174352 (14.75 GB)
telemt_user_octets_to_client{user="hello"} 53787018632 (50.09 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 70811.1 (19h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 567876
telemt_connections_bad_total 8105
telemt_handshake_timeouts_total 13097
telemt_upstream_connect_attempt_total 16574
telemt_upstream_connect_success_total 16421
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 16574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8081
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 22571
telemt_me_reconnect_success_total 11823
telemt_me_reader_eof_total 12816
telemt_me_idle_close_by_peer_total 12816
telemt_me_route_drop_no_conn_total 205826
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 486927
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1648
telemt_desync_full_logged_total 567
telemt_desync_suppressed_total 1081
telemt_desync_frames_bucket_total{bucket="1_2"} 418
telemt_desync_frames_bucket_total{bucket="3_10"} 739
telemt_desync_frames_bucket_total{bucket="gt_10"} 491
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12364
telemt_me_refill_failed_total 331
telemt_me_writer_restored_same_endpoint_total 11814
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 541
telemt_user_connections_total{user="hello"} 487758
telemt_user_connections_current{user="hello"} 728
telemt_user_octets_from_client{user="hello"} 6074306946 (5.66 GB)
telemt_user_octets_to_client{user="hello"} 158444133643 (147.56 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 70783.0 (19h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273107
telemt_connections_bad_total 56782
telemt_handshake_timeouts_total 3490
telemt_upstream_connect_attempt_total 20714
telemt_upstream_connect_success_total 20259
telemt_upstream_connect_fail_total 455
telemt_upstream_connect_attempts_per_request{bucket="1"} 20714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 282
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 455
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 36805
telemt_me_reconnect_success_total 16305
telemt_me_reader_eof_total 17535
telemt_me_idle_close_by_peer_total 17533
telemt_me_route_drop_no_conn_total 77325
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 201502
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1095
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 866
telemt_desync_frames_bucket_total{bucket="1_2"} 546
telemt_desync_frames_bucket_total{bucket="3_10"} 420
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 17220
telemt_me_refill_failed_total 636
telemt_me_writer_restored_same_endpoint_total 16297
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 915
telemt_user_connections_total{user="hello"} 201964
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 2585555935 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 73339385543 (68.30 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 70944.8 (19h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 656454
telemt_connections_bad_total 53850
telemt_handshake_timeouts_total 6525
telemt_upstream_connect_attempt_total 14167
telemt_upstream_connect_success_total 14092
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 14167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 20828
telemt_me_reconnect_success_total 10548
telemt_me_reader_eof_total 11510
telemt_me_idle_close_by_peer_total 11510
telemt_me_route_drop_no_conn_total 459275
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 657988
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 874
telemt_desync_full_logged_total 327
telemt_desync_suppressed_total 547
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 338
telemt_desync_frames_bucket_total{bucket="gt_10"} 313
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 11032
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 10534
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 484
telemt_user_connections_total{user="hello"} 562461
telemt_user_connections_current{user="hello"} 943
telemt_user_octets_from_client{user="hello"} 8435115848 (7.86 GB)
telemt_user_octets_to_client{user="hello"} 254959189736 (237.45 GB)
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 18711.1 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15178
telemt_connections_bad_total 65
telemt_handshake_timeouts_total 308
telemt_upstream_connect_attempt_total 10477
telemt_upstream_connect_success_total 10395
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 10477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 19552
telemt_me_reconnect_success_total 9287
telemt_me_reader_eof_total 9808
telemt_me_idle_close_by_peer_total 9808
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 5331
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14418
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 9697
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 9272
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 410
telemt_user_connections_total{user="hello"} 14519
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 429212277 (409.33 MB)
telemt_user_octets_to_client{user="hello"} 22706805026 (21.15 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 6
```