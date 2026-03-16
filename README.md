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

# Server Metrics 2026-03-16 17:00:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 12183.9 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127789
telemt_connections_bad_total 618
telemt_handshake_timeouts_total 3750
telemt_upstream_connect_attempt_total 2666
telemt_upstream_connect_success_total 2656
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3155
telemt_me_reconnect_success_total 1985
telemt_me_reader_eof_total 2053
telemt_me_idle_close_by_peer_total 2053
telemt_me_route_drop_no_conn_total 38433
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119257
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 629
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 485
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2034
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1983
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 119176
telemt_user_connections_current{user="hello"} 643
telemt_user_octets_from_client{user="hello"} 2195007436 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 68718853572 (64.00 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 6962.7 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48666
telemt_connections_bad_total 413
telemt_handshake_timeouts_total 1696
telemt_upstream_connect_attempt_total 1531
telemt_upstream_connect_success_total 1520
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 4630
telemt_me_reconnect_success_total 1125
telemt_me_reader_eof_total 1235
telemt_me_idle_close_by_peer_total 1235
telemt_me_route_drop_no_conn_total 30422
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45030
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 87
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1254
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 1120
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 44988
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 593672640 (566.17 MB)
telemt_user_octets_to_client{user="hello"} 14300342552 (13.32 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 12296.5 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50068
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 782
telemt_upstream_connect_attempt_total 3546
telemt_upstream_connect_success_total 3503
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 3546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 39616
telemt_me_reconnect_success_total 1855
telemt_me_reader_eof_total 2144
telemt_me_idle_close_by_peer_total 2144
telemt_me_route_drop_no_conn_total 17513
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45597
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 135
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2147
telemt_me_refill_failed_total 1179
telemt_me_writer_restored_same_endpoint_total 1811
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 46539
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 589818134 (562.49 MB)
telemt_user_octets_to_client{user="hello"} 11824414750 (11.01 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 12432.8 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97914
telemt_connections_bad_total 186
telemt_handshake_timeouts_total 1703
telemt_upstream_connect_attempt_total 2641
telemt_upstream_connect_success_total 2620
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 2641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1350
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 8271
telemt_me_reconnect_success_total 1920
telemt_me_reader_eof_total 2140
telemt_me_idle_close_by_peer_total 2140
telemt_me_route_drop_no_conn_total 37428
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92582
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 532
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 388
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2140
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 1916
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 92559
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 1309410396 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 24099632108 (22.44 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 9893.3 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57466
telemt_connections_bad_total 19162
telemt_handshake_timeouts_total 470
telemt_upstream_connect_attempt_total 2481
telemt_upstream_connect_success_total 2450
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 2481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_reconnect_attempts_total 2587
telemt_me_reconnect_success_total 1926
telemt_me_reader_eof_total 1990
telemt_me_idle_close_by_peer_total 1990
telemt_me_route_drop_no_conn_total 46708
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54829
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1978
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1926
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 35882
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 1944275760 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 27440446960 (25.56 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 12002.6 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140615
telemt_connections_bad_total 1533
telemt_handshake_timeouts_total 3029
telemt_upstream_connect_attempt_total 2660
telemt_upstream_connect_success_total 2660
telemt_upstream_connect_attempts_per_request{bucket="1"} 2660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 7015
telemt_me_reconnect_success_total 1992
telemt_me_reader_eof_total 2176
telemt_me_idle_close_by_peer_total 2176
telemt_me_route_drop_no_conn_total 64796
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130721
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 48
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2161
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 1987
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 130437
telemt_user_connections_current{user="hello"} 812
telemt_user_octets_from_client{user="hello"} 2811987504 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 48653822628 (45.31 GB)
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 101
```