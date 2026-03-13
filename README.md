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

# Server Metrics 2026-03-13 17:58:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 123906.1 (34h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 523245
telemt_connections_bad_total 8557
telemt_handshake_timeouts_total 12038
telemt_upstream_connect_attempt_total 31079
telemt_upstream_connect_success_total 30928
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 31079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3443
telemt_me_reconnect_attempts_total 29372
telemt_me_reconnect_success_total 24731
telemt_me_reader_eof_total 26426
telemt_me_idle_close_by_peer_total 26425
telemt_me_route_drop_no_conn_total 170590
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 454676
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1463
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 957
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 534
telemt_desync_frames_bucket_total{bucket="gt_10"} 607
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 25150
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 24715
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 454244
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 8379650288 (7.80 GB)
telemt_user_octets_to_client{user="hello"} 213806854824 (199.12 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 123799.1 (34h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258133
telemt_connections_bad_total 1951
telemt_handshake_timeouts_total 1825
telemt_upstream_connect_attempt_total 111538
telemt_upstream_connect_success_total 110693
telemt_upstream_connect_fail_total 845
telemt_upstream_connect_attempts_per_request{bucket="1"} 111538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1589
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 845
telemt_me_keepalive_timeout_total 1518
telemt_me_reconnect_attempts_total 127328
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29952
telemt_me_idle_close_by_peer_total 29952
telemt_me_route_drop_no_conn_total 82825
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166175
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
telemt_me_writer_removed_unexpected_total 29422
telemt_me_refill_failed_total 3161
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3389
telemt_user_connections_total{user="hello"} 244440
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 2554402722 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 75142636445 (69.98 GB)
telemt_user_msgs_from_client{user="hello"} 1230988
telemt_user_msgs_to_client{user="hello"} 7166872
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 123762.5 (34h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304779
telemt_connections_bad_total 2515
telemt_handshake_timeouts_total 17641
telemt_upstream_connect_attempt_total 33024
telemt_upstream_connect_success_total 33020
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 33024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17670
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2663
telemt_me_reconnect_attempts_total 28020
telemt_me_reconnect_success_total 26791
telemt_me_reader_eof_total 28727
telemt_me_idle_close_by_peer_total 28727
telemt_me_route_drop_no_conn_total 108830
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 273914
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
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 27089
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 26771
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 273825
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 10176780676 (9.48 GB)
telemt_user_octets_to_client{user="hello"} 112535661000 (104.81 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 123738.2 (34h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411142
telemt_connections_bad_total 15106
telemt_handshake_timeouts_total 3876
telemt_upstream_connect_attempt_total 60318
telemt_upstream_connect_success_total 50066
telemt_upstream_connect_fail_total 10252
telemt_upstream_connect_attempts_per_request{bucket="1"} 60318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 283
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10252
telemt_me_keepalive_timeout_total 4660
telemt_me_reconnect_attempts_total 114504
telemt_me_reconnect_success_total 24848
telemt_me_reader_eof_total 28352
telemt_me_idle_close_by_peer_total 28345
telemt_me_route_drop_no_conn_total 141642
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 343216
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1353
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 950
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 521
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 27963
telemt_me_refill_failed_total 2796
telemt_me_writer_restored_same_endpoint_total 24838
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3115
telemt_user_connections_total{user="hello"} 362106
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 8374931287 (7.80 GB)
telemt_user_octets_to_client{user="hello"} 129435528572 (120.55 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 73909.6 (20h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121474
telemt_connections_bad_total 15331
telemt_handshake_timeouts_total 1396
telemt_upstream_connect_attempt_total 29143
telemt_upstream_connect_success_total 28873
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 29143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13851
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 1179
telemt_me_reconnect_attempts_total 33639
telemt_me_reconnect_success_total 20251
telemt_me_reader_eof_total 21706
telemt_me_idle_close_by_peer_total 21706
telemt_me_route_drop_no_conn_total 38140
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95951
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 464
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 370
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 20853
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 20233
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 602
telemt_user_connections_total{user="hello"} 100848
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 1197648481 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 33495634603 (31.20 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 123695.0 (34h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 756180
telemt_connections_bad_total 24762
telemt_handshake_timeouts_total 24479
telemt_upstream_connect_attempt_total 25741
telemt_upstream_connect_success_total 25604
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 25741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 2984
telemt_me_reconnect_attempts_total 24097
telemt_me_reconnect_success_total 19454
telemt_me_reader_eof_total 20878
telemt_me_idle_close_by_peer_total 20875
telemt_me_route_drop_no_conn_total 358288
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 709431
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
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 19853
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19447
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 399
telemt_user_connections_total{user="hello"} 682319
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 11977158592 (11.15 GB)
telemt_user_octets_to_client{user="hello"} 340257228316 (316.89 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 75
```