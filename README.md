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

# Server Metrics 2026-03-13 16:57:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 120242.2 (33h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 504012
telemt_connections_bad_total 5274
telemt_handshake_timeouts_total 10732
telemt_upstream_connect_attempt_total 29868
telemt_upstream_connect_success_total 29722
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 29868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2709
telemt_me_reconnect_attempts_total 27254
telemt_me_reconnect_success_total 23708
telemt_me_reader_eof_total 25332
telemt_me_idle_close_by_peer_total 25331
telemt_me_route_drop_no_conn_total 164215
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 440557
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1417
telemt_desync_full_logged_total 495
telemt_desync_suppressed_total 922
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 510
telemt_desync_frames_bucket_total{bucket="gt_10"} 593
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24076
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 23692
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 440128
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 8001220796 (7.45 GB)
telemt_user_octets_to_client{user="hello"} 204211267120 (190.19 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 120135.1 (33h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246390
telemt_connections_bad_total 1885
telemt_handshake_timeouts_total 1796
telemt_upstream_connect_attempt_total 101514
telemt_upstream_connect_success_total 100696
telemt_upstream_connect_fail_total 818
telemt_upstream_connect_attempts_per_request{bucket="1"} 101514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1351
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 818
telemt_me_keepalive_timeout_total 1469
telemt_me_reconnect_attempts_total 121824
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29780
telemt_me_idle_close_by_peer_total 29780
telemt_me_route_drop_no_conn_total 82181
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164771
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 29
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
telemt_me_writer_removed_unexpected_total 29250
telemt_me_refill_failed_total 2989
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3217
telemt_user_connections_total{user="hello"} 233215
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 2436409446 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 72183607032 (67.23 GB)
telemt_user_msgs_from_client{user="hello"} 1071223
telemt_user_msgs_to_client{user="hello"} 6288764
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 120099.2 (33h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292706
telemt_connections_bad_total 2449
telemt_handshake_timeouts_total 15248
telemt_upstream_connect_attempt_total 32132
telemt_upstream_connect_success_total 32128
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 32132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17180
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2476
telemt_me_reconnect_attempts_total 27301
telemt_me_reconnect_success_total 26076
telemt_me_reader_eof_total 27949
telemt_me_idle_close_by_peer_total 27949
telemt_me_route_drop_no_conn_total 104875
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264664
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 26367
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 26056
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 264573
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 10112560008 (9.42 GB)
telemt_user_octets_to_client{user="hello"} 110587966156 (102.99 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 120074.4 (33h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 397790
telemt_connections_bad_total 15099
telemt_handshake_timeouts_total 3836
telemt_upstream_connect_attempt_total 51627
telemt_upstream_connect_success_total 41417
telemt_upstream_connect_fail_total 10209
telemt_upstream_connect_attempts_per_request{bucket="1"} 51626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16958
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10209
telemt_me_keepalive_timeout_total 4218
telemt_me_reconnect_attempts_total 111319
telemt_me_reconnect_success_total 24392
telemt_me_reader_eof_total 27813
telemt_me_idle_close_by_peer_total 27806
telemt_me_route_drop_no_conn_total 139701
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338528
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 26
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
telemt_me_writer_removed_unexpected_total 27416
telemt_me_refill_failed_total 2711
telemt_me_writer_restored_same_endpoint_total 24382
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3024
telemt_user_connections_total{user="hello"} 349408
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 8249948717 (7.68 GB)
telemt_user_octets_to_client{user="hello"} 127362911032 (118.62 GB)
telemt_user_msgs_from_client{user="hello"} 358836
telemt_user_msgs_to_client{user="hello"} 505615
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 70245.9 (19h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112735
telemt_connections_bad_total 14584
telemt_handshake_timeouts_total 1377
telemt_upstream_connect_attempt_total 28151
telemt_upstream_connect_success_total 27901
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 28151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13348
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 1118
telemt_me_reconnect_attempts_total 30666
telemt_me_reconnect_success_total 19488
telemt_me_reader_eof_total 20853
telemt_me_idle_close_by_peer_total 20853
telemt_me_route_drop_no_conn_total 34990
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88237
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 20010
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 19470
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 522
telemt_user_connections_total{user="hello"} 93136
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 1118360229 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 28750501339 (26.78 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 120031.2 (33h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 732276
telemt_connections_bad_total 24642
telemt_handshake_timeouts_total 24297
telemt_upstream_connect_attempt_total 25137
telemt_upstream_connect_success_total 25010
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 25137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13237
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 2646
telemt_me_reconnect_attempts_total 23670
telemt_me_reconnect_success_total 19036
telemt_me_reader_eof_total 20426
telemt_me_idle_close_by_peer_total 20423
telemt_me_route_drop_no_conn_total 345942
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 686521
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 667
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 19422
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19029
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 659409
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 11402746160 (10.62 GB)
telemt_user_octets_to_client{user="hello"} 334469687636 (311.50 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 63
```