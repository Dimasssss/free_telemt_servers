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

# Server Metrics 2026-03-13 17:32:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 122378.5 (33h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 516403
telemt_connections_bad_total 7439
telemt_handshake_timeouts_total 11726
telemt_upstream_connect_attempt_total 30570
telemt_upstream_connect_success_total 30419
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 30570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3417
telemt_me_reconnect_attempts_total 27862
telemt_me_reconnect_success_total 24312
telemt_me_reader_eof_total 25938
telemt_me_idle_close_by_peer_total 25937
telemt_me_route_drop_no_conn_total 167850
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 449386
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1459
telemt_desync_full_logged_total 505
telemt_desync_suppressed_total 954
telemt_desync_frames_bucket_total{bucket="1_2"} 321
telemt_desync_frames_bucket_total{bucket="3_10"} 533
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24686
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 24296
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 374
telemt_user_connections_total{user="hello"} 448955
telemt_user_connections_current{user="hello"} 355
telemt_user_octets_from_client{user="hello"} 8291414020 (7.72 GB)
telemt_user_octets_to_client{user="hello"} 211148208344 (196.65 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 122272.2 (33h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253428
telemt_connections_bad_total 1945
telemt_handshake_timeouts_total 1809
telemt_upstream_connect_attempt_total 107617
telemt_upstream_connect_success_total 106785
telemt_upstream_connect_fail_total 832
telemt_upstream_connect_attempts_per_request{bucket="1"} 107617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 832
telemt_me_keepalive_timeout_total 1513
telemt_me_reconnect_attempts_total 124576
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29866
telemt_me_idle_close_by_peer_total 29866
telemt_me_route_drop_no_conn_total 82391
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165453
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29336
telemt_me_refill_failed_total 3075
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3303
telemt_user_connections_total{user="hello"} 239898
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 2509221340 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 73814523718 (68.75 GB)
telemt_user_msgs_from_client{user="hello"} 1171581
telemt_user_msgs_to_client{user="hello"} 6771985
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 122235.9 (33h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 299832
telemt_connections_bad_total 2492
telemt_handshake_timeouts_total 16609
telemt_upstream_connect_attempt_total 32634
telemt_upstream_connect_success_total 32630
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 32634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17458
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2592
telemt_me_reconnect_attempts_total 27716
telemt_me_reconnect_success_total 26487
telemt_me_reader_eof_total 28394
telemt_me_idle_close_by_peer_total 28394
telemt_me_route_drop_no_conn_total 107246
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 270161
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 26784
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 26467
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 270070
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 10156643340 (9.46 GB)
telemt_user_octets_to_client{user="hello"} 111758587924 (104.08 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 122211.1 (33h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 406570
telemt_connections_bad_total 15106
telemt_handshake_timeouts_total 3866
telemt_upstream_connect_attempt_total 59265
telemt_upstream_connect_success_total 49022
telemt_upstream_connect_fail_total 10243
telemt_upstream_connect_attempts_per_request{bucket="1"} 59265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17677
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 276
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10243
telemt_me_keepalive_timeout_total 4654
telemt_me_reconnect_attempts_total 114209
telemt_me_reconnect_success_total 24557
telemt_me_reader_eof_total 28052
telemt_me_idle_close_by_peer_total 28045
telemt_me_route_drop_no_conn_total 140235
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339469
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1350
telemt_desync_full_logged_total 402
telemt_desync_suppressed_total 948
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 27667
telemt_me_refill_failed_total 2796
telemt_me_writer_restored_same_endpoint_total 24547
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3110
telemt_user_connections_total{user="hello"} 357698
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 8334826737 (7.76 GB)
telemt_user_octets_to_client{user="hello"} 128724298966 (119.88 GB)
telemt_user_msgs_from_client{user="hello"} 448053
telemt_user_msgs_to_client{user="hello"} 840887
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 72382.7 (20h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118074
telemt_connections_bad_total 15037
telemt_handshake_timeouts_total 1390
telemt_upstream_connect_attempt_total 28714
telemt_upstream_connect_success_total 28451
telemt_upstream_connect_fail_total 263
telemt_upstream_connect_attempts_per_request{bucket="1"} 28714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 263
telemt_me_keepalive_timeout_total 1163
telemt_me_reconnect_attempts_total 33303
telemt_me_reconnect_success_total 19916
telemt_me_reader_eof_total 21368
telemt_me_idle_close_by_peer_total 21368
telemt_me_route_drop_no_conn_total 36793
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92912
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 410
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 326
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 224
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 20515
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 19898
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 599
telemt_user_connections_total{user="hello"} 97810
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 1174603545 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 30863241203 (28.74 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 122168.0 (33h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 745961
telemt_connections_bad_total 24648
telemt_handshake_timeouts_total 24405
telemt_upstream_connect_attempt_total 25486
telemt_upstream_connect_success_total 25352
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 25486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 2932
telemt_me_reconnect_attempts_total 23932
telemt_me_reconnect_success_total 19289
telemt_me_reader_eof_total 20703
telemt_me_idle_close_by_peer_total 20700
telemt_me_route_drop_no_conn_total 352707
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 699682
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 680
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 19687
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19282
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 398
telemt_user_connections_total{user="hello"} 672566
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 11837385956 (11.02 GB)
telemt_user_octets_to_client{user="hello"} 337931582060 (314.72 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 65
```