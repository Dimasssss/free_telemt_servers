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

# Server Metrics 2026-03-19 13:43:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 499.8 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25042
telemt_connections_current 76
telemt_connections_me_current 76
telemt_handshake_timeouts_total 21638
telemt_upstream_connect_attempt_total 366
telemt_upstream_connect_success_total 365
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 237
telemt_me_reconnect_success_total 233
telemt_me_reader_eof_total 165
telemt_me_idle_close_by_peer_total 165
telemt_me_route_drop_no_conn_total 308
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1307
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_desync_total 22
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_close_signal_drop_total 13
telemt_me_writer_removed_unexpected_total 178
telemt_me_writer_restored_same_endpoint_total 217
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 10
telemt_me_async_recovery_trigger_total 102
telemt_user_connections_total{user="hello"} 1379
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 28491555 (27.17 MB)
telemt_user_octets_to_client{user="hello"} 420522300 (401.04 MB)
telemt_user_msgs_from_client{user="hello"} 261
telemt_user_msgs_to_client{user="hello"} 430
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 3635.5 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402218
telemt_connections_bad_total 10891
telemt_connections_current 3581
telemt_connections_me_current 3581
telemt_handshake_timeouts_total 5551
telemt_upstream_connect_attempt_total 2105
telemt_upstream_connect_success_total 2093
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 2364
telemt_me_reconnect_success_total 661
telemt_me_reader_eof_total 668
telemt_me_idle_close_by_peer_total 668
telemt_me_route_drop_no_conn_total 355046
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360341
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1057
telemt_desync_full_logged_total 354
telemt_desync_suppressed_total 703
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 408
telemt_desync_frames_bucket_total{bucket="gt_10"} 477
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 695
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 606
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 361206
telemt_user_connections_current{user="hello"} 3581
telemt_user_octets_from_client{user="hello"} 5376146586 (5.01 GB)
telemt_user_octets_to_client{user="hello"} 89245419194 (83.12 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1317
telemt_user_unique_ips_recent_window{user="hello"} 549
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 3613.9 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 469418
telemt_connections_bad_total 41704
telemt_connections_current 2880
telemt_connections_me_current 2880
telemt_handshake_timeouts_total 4826
telemt_upstream_connect_attempt_total 527
telemt_upstream_connect_success_total 523
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 1220
telemt_me_reconnect_success_total 322
telemt_me_reader_eof_total 252
telemt_me_idle_close_by_peer_total 251
telemt_me_route_drop_no_conn_total 489991
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 347691
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1117
telemt_desync_full_logged_total 275
telemt_desync_suppressed_total 842
telemt_desync_frames_bucket_total{bucket="1_2"} 326
telemt_desync_frames_bucket_total{bucket="3_10"} 414
telemt_desync_frames_bucket_total{bucket="gt_10"} 377
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 27
telemt_me_writer_removed_unexpected_total 272
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 321
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 345525
telemt_user_connections_current{user="hello"} 2880
telemt_user_octets_from_client{user="hello"} 2582159644 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 78456731384 (73.07 GB)
telemt_user_unique_ips_current{user="hello"} 1031
telemt_user_unique_ips_recent_window{user="hello"} 417
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 3601.4 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333570
telemt_connections_bad_total 37076
telemt_connections_current 2778
telemt_connections_me_current 2778
telemt_handshake_timeouts_total 5042
telemt_upstream_connect_attempt_total 4053
telemt_upstream_connect_success_total 3903
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 4053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 393
telemt_me_reconnect_success_total 377
telemt_me_reader_eof_total 348
telemt_me_idle_close_by_peer_total 347
telemt_me_route_drop_no_conn_total 201168
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 263298
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 960
telemt_desync_full_logged_total 318
telemt_desync_suppressed_total 642
telemt_desync_frames_bucket_total{bucket="1_2"} 178
telemt_desync_frames_bucket_total{bucket="3_10"} 339
telemt_desync_frames_bucket_total{bucket="gt_10"} 443
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 366
telemt_me_writer_restored_same_endpoint_total 374
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 402
telemt_user_connections_total{user="hello"} 266430
telemt_user_connections_current{user="hello"} 2778
telemt_user_octets_from_client{user="hello"} 3085569387 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 59954311138 (55.84 GB)
telemt_user_msgs_from_client{user="hello"} 5613
telemt_user_msgs_to_client{user="hello"} 6373
telemt_user_unique_ips_current{user="hello"} 963
telemt_user_unique_ips_recent_window{user="hello"} 430
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 57324.5 (15h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3890149
telemt_connections_bad_total 758071
telemt_connections_current 3569
telemt_connections_me_current 3569
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 77616
telemt_upstream_connect_attempt_total 61971
telemt_upstream_connect_success_total 59488
telemt_upstream_connect_fail_total 2483
telemt_upstream_connect_attempts_per_request{bucket="1"} 61971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7044
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1014
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2483
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 70499
telemt_me_reconnect_success_total 7443
telemt_me_reader_eof_total 7778
telemt_me_idle_close_by_peer_total 7775
telemt_me_route_drop_no_conn_total 1727111
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2630261
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11466
telemt_desync_full_logged_total 3534
telemt_desync_suppressed_total 7932
telemt_desync_frames_bucket_total{bucket="1_2"} 2011
telemt_desync_frames_bucket_total{bucket="3_10"} 4912
telemt_desync_frames_bucket_total{bucket="gt_10"} 4543
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7572
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 7419
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 2678990
telemt_user_connections_current{user="hello"} 3569
telemt_user_octets_from_client{user="hello"} 43513166735 (40.52 GB)
telemt_user_octets_to_client{user="hello"} 972466563876 (905.68 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1186
telemt_user_unique_ips_recent_window{user="hello"} 557
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 3566.7 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93685
telemt_connections_bad_total 4922
telemt_connections_current 936
telemt_connections_me_current 936
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 4632
telemt_upstream_connect_attempt_total 3239
telemt_upstream_connect_success_total 3103
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 3239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1887
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_reconnect_attempts_total 385
telemt_me_reconnect_success_total 370
telemt_me_reader_eof_total 315
telemt_me_idle_close_by_peer_total 315
telemt_me_route_drop_no_conn_total 73822
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77797
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 149
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 89
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 29
telemt_me_writer_removed_unexpected_total 331
telemt_me_writer_restored_same_endpoint_total 361
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 80442
telemt_user_connections_current{user="hello"} 936
telemt_user_octets_from_client{user="hello"} 1094561344 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 18136607742 (16.89 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 3565.9 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253498
telemt_connections_bad_total 23196
telemt_connections_current 3296
telemt_connections_me_current 3296
telemt_handshake_timeouts_total 4353
telemt_upstream_connect_attempt_total 525
telemt_upstream_connect_success_total 522
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 326
telemt_me_reconnect_success_total 321
telemt_me_reader_eof_total 317
telemt_me_idle_close_by_peer_total 317
telemt_me_route_drop_no_conn_total 74333
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217881
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 991
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 703
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 467
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 328
telemt_me_writer_restored_same_endpoint_total 304
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 217811
telemt_user_connections_current{user="hello"} 3296
telemt_user_octets_from_client{user="hello"} 2626903960 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 90845038844 (84.61 GB)
telemt_user_unique_ips_current{user="hello"} 1071
telemt_user_unique_ips_recent_window{user="hello"} 474
```