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

# Server Metrics 2026-03-14 16:53:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 13045.1 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74268
telemt_connections_bad_total 12380
telemt_handshake_timeouts_total 334
telemt_upstream_connect_attempt_total 3220
telemt_upstream_connect_success_total 3218
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1592
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 2536
telemt_me_reconnect_success_total 2507
telemt_me_reader_eof_total 2638
telemt_me_idle_close_by_peer_total 2638
telemt_me_route_drop_no_conn_total 27271
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59393
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 218
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2557
telemt_me_writer_restored_same_endpoint_total 2489
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 59325
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 1162915824 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 26653659232 (24.82 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 13043.7 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30770
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 645
telemt_upstream_connect_attempt_total 3737
telemt_upstream_connect_success_total 3706
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 3737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 5564
telemt_me_reconnect_success_total 2994
telemt_me_reader_eof_total 3163
telemt_me_idle_close_by_peer_total 3163
telemt_me_route_drop_no_conn_total 15436
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28717
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 3119
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 2989
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 28698
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 351252348 (334.98 MB)
telemt_user_octets_to_client{user="hello"} 11082719472 (10.32 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 13048.6 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31065
telemt_connections_bad_total 347
telemt_handshake_timeouts_total 1597
telemt_upstream_connect_attempt_total 5391
telemt_upstream_connect_success_total 5340
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 5391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2719
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 100788
telemt_me_reconnect_success_total 4311
telemt_me_reader_eof_total 4555
telemt_me_idle_close_by_peer_total 4555
telemt_me_route_drop_no_conn_total 11713
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27202
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 4522
telemt_me_refill_failed_total 3126
telemt_me_writer_restored_same_endpoint_total 4273
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 27485
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 2757329033 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 13982560230 (13.02 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 13053.0 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40567
telemt_connections_bad_total 110
telemt_handshake_timeouts_total 259
telemt_upstream_connect_attempt_total 3564
telemt_upstream_connect_success_total 3547
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 2862
telemt_me_reconnect_success_total 2844
telemt_me_reader_eof_total 2952
telemt_me_idle_close_by_peer_total 2952
telemt_me_route_drop_no_conn_total 19586
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38598
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 374
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 279
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2870
telemt_me_writer_restored_same_endpoint_total 2842
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 38477
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 409784632 (390.80 MB)
telemt_user_octets_to_client{user="hello"} 12839817620 (11.96 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 13046.3 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28825
telemt_connections_bad_total 2567
telemt_handshake_timeouts_total 1440
telemt_upstream_connect_attempt_total 3026
telemt_upstream_connect_success_total 2988
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 3026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 8798
telemt_me_reconnect_success_total 2277
telemt_me_reader_eof_total 2531
telemt_me_idle_close_by_peer_total 2531
telemt_me_route_drop_no_conn_total 10106
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23525
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 97
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2495
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 2273
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 23520
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 205724180 (196.19 MB)
telemt_user_octets_to_client{user="hello"} 6947716808 (6.47 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 13045.8 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104945
telemt_connections_bad_total 4387
telemt_handshake_timeouts_total 1129
telemt_upstream_connect_attempt_total 2728
telemt_upstream_connect_success_total 2674
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 2728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1324
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 6956
telemt_me_reconnect_success_total 1961
telemt_me_reader_eof_total 2156
telemt_me_idle_close_by_peer_total 2156
telemt_me_route_drop_no_conn_total 52255
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93836
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 34
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2136
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 1957
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 93731
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 1536621876 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 45710430532 (42.57 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 72
```