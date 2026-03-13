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

# Server Metrics 2026-03-13 13:58:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 109529.6 (30h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451904
telemt_connections_bad_total 3215
telemt_handshake_timeouts_total 8503
telemt_upstream_connect_attempt_total 27620
telemt_upstream_connect_success_total 27490
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 27620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15018
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2410
telemt_me_reconnect_attempts_total 25539
telemt_me_reconnect_success_total 22010
telemt_me_reader_eof_total 23507
telemt_me_idle_close_by_peer_total 23506
telemt_me_route_drop_no_conn_total 145005
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 394921
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1316
telemt_desync_full_logged_total 467
telemt_desync_suppressed_total 849
telemt_desync_frames_bucket_total{bucket="1_2"} 284
telemt_desync_frames_bucket_total{bucket="3_10"} 479
telemt_desync_frames_bucket_total{bucket="gt_10"} 553
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 22349
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21994
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 339
telemt_user_connections_total{user="hello"} 394500
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 7143306348 (6.65 GB)
telemt_user_octets_to_client{user="hello"} 180752680360 (168.34 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 109422.6 (30h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211787
telemt_connections_bad_total 1745
telemt_handshake_timeouts_total 1529
telemt_upstream_connect_attempt_total 71378
telemt_upstream_connect_success_total 70640
telemt_upstream_connect_fail_total 738
telemt_upstream_connect_attempts_per_request{bucket="1"} 71378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 664
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 738
telemt_me_keepalive_timeout_total 1396
telemt_me_reconnect_attempts_total 105292
telemt_me_reconnect_success_total 26016
telemt_me_reader_eof_total 29253
telemt_me_idle_close_by_peer_total 29253
telemt_me_route_drop_no_conn_total 79927
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161102
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 25
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
telemt_me_writer_removed_unexpected_total 28717
telemt_me_refill_failed_total 2473
telemt_me_writer_restored_same_endpoint_total 25999
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2701
telemt_user_connections_total{user="hello"} 200040
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 2034989196 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 64596371120 (60.16 GB)
telemt_user_msgs_from_client{user="hello"} 577297
telemt_user_msgs_to_client{user="hello"} 4015071
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 109386.5 (30h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257491
telemt_connections_bad_total 2081
telemt_handshake_timeouts_total 10555
telemt_upstream_connect_attempt_total 29414
telemt_upstream_connect_success_total 29410
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 29414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2280
telemt_me_reconnect_attempts_total 25108
telemt_me_reconnect_success_total 23893
telemt_me_reader_eof_total 25598
telemt_me_idle_close_by_peer_total 25598
telemt_me_route_drop_no_conn_total 93684
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235572
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 24151
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23873
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 235490
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 9473280980 (8.82 GB)
telemt_user_octets_to_client{user="hello"} 100980533988 (94.05 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 109361.9 (30h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355672
telemt_connections_bad_total 15039
telemt_handshake_timeouts_total 3425
telemt_upstream_connect_attempt_total 41379
telemt_upstream_connect_success_total 31261
telemt_upstream_connect_fail_total 10118
telemt_upstream_connect_attempts_per_request{bucket="1"} 41379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15246
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 209
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10118
telemt_me_keepalive_timeout_total 4128
telemt_me_reconnect_attempts_total 96566
telemt_me_reconnect_success_total 22737
telemt_me_reader_eof_total 25736
telemt_me_idle_close_by_peer_total 25729
telemt_me_route_drop_no_conn_total 127406
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 306730
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1168
telemt_desync_full_logged_total 344
telemt_desync_suppressed_total 824
telemt_desync_frames_bucket_total{bucket="1_2"} 287
telemt_desync_frames_bucket_total{bucket="3_10"} 441
telemt_desync_frames_bucket_total{bucket="gt_10"} 440
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 25334
telemt_me_refill_failed_total 2302
telemt_me_writer_restored_same_endpoint_total 22727
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2597
telemt_user_connections_total{user="hello"} 309640
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 6755184550 (6.29 GB)
telemt_user_octets_to_client{user="hello"} 115697811821 (107.75 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 59533.4 (16h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89538
telemt_connections_bad_total 12016
telemt_handshake_timeouts_total 1207
telemt_upstream_connect_attempt_total 24805
telemt_upstream_connect_success_total 24601
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 24805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 1003
telemt_me_reconnect_attempts_total 26610
telemt_me_reconnect_success_total 16690
telemt_me_reader_eof_total 17910
telemt_me_idle_close_by_peer_total 17910
telemt_me_route_drop_no_conn_total 26640
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68564
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 194
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 17146
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 16672
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 456
telemt_user_connections_total{user="hello"} 73464
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 893278465 (851.90 MB)
telemt_user_octets_to_client{user="hello"} 21581727591 (20.10 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 109318.4 (30h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 638662
telemt_connections_bad_total 17986
telemt_handshake_timeouts_total 18748
telemt_upstream_connect_attempt_total 23059
telemt_upstream_connect_success_total 22941
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 23059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 2511
telemt_me_reconnect_attempts_total 22123
telemt_me_reconnect_success_total 17498
telemt_me_reader_eof_total 18788
telemt_me_idle_close_by_peer_total 18785
telemt_me_route_drop_no_conn_total 309596
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 607492
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 475
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 297
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 17870
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17491
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 372
telemt_user_connections_total{user="hello"} 580440
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 10167362864 (9.47 GB)
telemt_user_octets_to_client{user="hello"} 307918629284 (286.77 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 85
```