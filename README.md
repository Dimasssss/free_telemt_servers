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

# Server Metrics 2026-03-16 17:46:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 14935.6 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152656
telemt_connections_bad_total 666
telemt_handshake_timeouts_total 3992
telemt_upstream_connect_attempt_total 3213
telemt_upstream_connect_success_total 3201
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1678
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3570
telemt_me_reconnect_success_total 2400
telemt_me_reader_eof_total 2486
telemt_me_idle_close_by_peer_total 2485
telemt_me_route_drop_no_conn_total 46074
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142983
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 711
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 543
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 254
telemt_desync_frames_bucket_total{bucket="gt_10"} 193
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2450
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2398
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 142901
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 2589677380 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 82028348648 (76.39 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 9714.0 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69336
telemt_connections_bad_total 583
telemt_handshake_timeouts_total 3136
telemt_upstream_connect_attempt_total 2097
telemt_upstream_connect_success_total 2085
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 181
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 5065
telemt_me_reconnect_success_total 1557
telemt_me_reader_eof_total 1694
telemt_me_idle_close_by_peer_total 1694
telemt_me_route_drop_no_conn_total 40179
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63130
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1694
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 1552
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 63071
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 781705596 (745.49 MB)
telemt_user_octets_to_client{user="hello"} 18559306052 (17.28 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 15048.5 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60713
telemt_connections_bad_total 77
telemt_handshake_timeouts_total 870
telemt_upstream_connect_attempt_total 4489
telemt_upstream_connect_success_total 4442
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 4489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2055
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 41542
telemt_me_reconnect_success_total 2657
telemt_me_reader_eof_total 2985
telemt_me_idle_close_by_peer_total 2985
telemt_me_route_drop_no_conn_total 21222
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55849
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 151
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2991
telemt_me_refill_failed_total 1214
telemt_me_writer_restored_same_endpoint_total 2613
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 334
telemt_user_connections_total{user="hello"} 56788
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 700809334 (668.34 MB)
telemt_user_octets_to_client{user="hello"} 15729405122 (14.65 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 15184.5 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118615
telemt_connections_bad_total 221
telemt_handshake_timeouts_total 1739
telemt_upstream_connect_attempt_total 3267
telemt_upstream_connect_success_total 3241
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1670
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8766
telemt_me_reconnect_success_total 2410
telemt_me_reader_eof_total 2656
telemt_me_idle_close_by_peer_total 2655
telemt_me_route_drop_no_conn_total 43771
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112497
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 627
telemt_desync_full_logged_total 173
telemt_desync_suppressed_total 454
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 253
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2640
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 2406
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 112469
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 1546508472 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 28304068504 (26.36 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 12645.0 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68788
telemt_connections_bad_total 20232
telemt_handshake_timeouts_total 557
telemt_upstream_connect_attempt_total 3216
telemt_upstream_connect_success_total 3175
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 3215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 4171
telemt_me_reconnect_success_total 2517
telemt_me_reader_eof_total 2625
telemt_me_idle_close_by_peer_total 2625
telemt_me_route_drop_no_conn_total 50465
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64484
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2606
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 2517
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 45536
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 2053540476 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 31991737764 (29.79 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 14752.9 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171823
telemt_connections_bad_total 2080
telemt_handshake_timeouts_total 3383
telemt_upstream_connect_attempt_total 3087
telemt_upstream_connect_success_total 3087
telemt_upstream_connect_attempts_per_request{bucket="1"} 3087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 7313
telemt_me_reconnect_success_total 2286
telemt_me_reader_eof_total 2493
telemt_me_idle_close_by_peer_total 2492
telemt_me_route_drop_no_conn_total 76975
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159311
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 49
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2462
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 2280
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 159029
telemt_user_connections_current{user="hello"} 738
telemt_user_octets_from_client{user="hello"} 3131551556 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 61041025432 (56.85 GB)
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 86
```