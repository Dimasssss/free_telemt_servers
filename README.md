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

# Server Metrics 2026-03-15 13:16:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 54110.4 (15h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240969
telemt_connections_bad_total 2272
telemt_handshake_timeouts_total 5151
telemt_upstream_connect_attempt_total 13577
telemt_upstream_connect_success_total 13505
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 13577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7471
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 14156
telemt_me_reconnect_success_total 10781
telemt_me_reader_eof_total 11523
telemt_me_idle_close_by_peer_total 11523
telemt_me_route_drop_no_conn_total 431090
telemt_me_route_drop_channel_closed_total 66
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 285359
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1636
telemt_desync_full_logged_total 649
telemt_desync_suppressed_total 987
telemt_desync_frames_bucket_total{bucket="1_2"} 282
telemt_desync_frames_bucket_total{bucket="3_10"} 653
telemt_desync_frames_bucket_total{bucket="gt_10"} 701
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10999
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 10750
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 224464
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 4731697124 (4.41 GB)
telemt_user_octets_to_client{user="hello"} 201421678072 (187.59 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 54116.7 (15h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87543
telemt_connections_bad_total 2746
telemt_handshake_timeouts_total 7858
telemt_upstream_connect_attempt_total 14841
telemt_upstream_connect_success_total 14841
telemt_upstream_connect_attempts_per_request{bucket="1"} 14841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 14423
telemt_me_reconnect_success_total 12081
telemt_me_reader_eof_total 12932
telemt_me_idle_close_by_peer_total 12932
telemt_me_route_drop_no_conn_total 37518
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74245
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 12289
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 12065
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 74242
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 1476085772 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 36506422472 (34.00 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 54109.4 (15h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90096
telemt_connections_bad_total 1609
telemt_handshake_timeouts_total 2720
telemt_upstream_connect_attempt_total 15678
telemt_upstream_connect_success_total 15670
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 15678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8828
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 15063
telemt_me_reconnect_success_total 12914
telemt_me_reader_eof_total 13823
telemt_me_idle_close_by_peer_total 13823
telemt_me_route_drop_no_conn_total 34765
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81881
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 13105
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 12906
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 81791
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 9913995436 (9.23 GB)
telemt_user_octets_to_client{user="hello"} 50271894960 (46.82 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 54109.1 (15h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123194
telemt_connections_bad_total 429
telemt_handshake_timeouts_total 799
telemt_upstream_connect_attempt_total 12712
telemt_upstream_connect_success_total 12710
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 12712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 10039
telemt_me_reconnect_success_total 9980
telemt_me_reader_eof_total 10638
telemt_me_idle_close_by_peer_total 10638
telemt_me_route_drop_no_conn_total 48330
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112216
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 238
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 142
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 10093
telemt_me_writer_restored_same_endpoint_total 9969
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 112135
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 2139694568 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 59245301956 (55.18 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 29180.6 (8h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71364
telemt_connections_bad_total 20522
telemt_handshake_timeouts_total 1364
telemt_upstream_connect_attempt_total 9338
telemt_upstream_connect_success_total 9275
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 9338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5081
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_reconnect_attempts_total 102045
telemt_me_reconnect_success_total 7623
telemt_me_reader_eof_total 7967
telemt_me_idle_close_by_peer_total 7967
telemt_me_route_drop_no_conn_total 23632
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47928
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 116
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 91
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 7621
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 7519
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 48064
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 736397205 (702.28 MB)
telemt_user_octets_to_client{user="hello"} 19284998219 (17.96 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 54108.6 (15h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 318368
telemt_connections_bad_total 47877
telemt_handshake_timeouts_total 2533
telemt_upstream_connect_attempt_total 11592
telemt_upstream_connect_success_total 11523
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 11592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5745
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 8841
telemt_me_reconnect_success_total 8780
telemt_me_reader_eof_total 9329
telemt_me_idle_close_by_peer_total 9329
telemt_me_route_drop_no_conn_total 144687
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 258619
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 252
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 180
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 74
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 8861
telemt_me_writer_restored_same_endpoint_total 8753
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 256907
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 5221774504 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 123868808740 (115.36 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 84
```