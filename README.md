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

# Server Metrics 2026-03-14 14:35:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 4769.5 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27314
telemt_connections_bad_total 4586
telemt_handshake_timeouts_total 154
telemt_upstream_connect_attempt_total 1175
telemt_upstream_connect_success_total 1174
telemt_upstream_connect_attempts_per_request{bucket="1"} 1174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 885
telemt_me_reconnect_success_total 871
telemt_me_reader_eof_total 892
telemt_me_idle_close_by_peer_total 892
telemt_me_route_drop_no_conn_total 10991
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22084
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 28
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 889
telemt_me_writer_restored_same_endpoint_total 853
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 22025
telemt_user_connections_current{user="hello"} 355
telemt_user_octets_from_client{user="hello"} 351437340 (335.16 MB)
telemt_user_octets_to_client{user="hello"} 8457135920 (7.88 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 4767.7 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11474
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 480
telemt_upstream_connect_attempt_total 1307
telemt_upstream_connect_success_total 1283
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 1307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1009
telemt_me_reconnect_success_total 982
telemt_me_reader_eof_total 1004
telemt_me_idle_close_by_peer_total 1004
telemt_me_route_drop_no_conn_total 5565
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10594
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1002
telemt_me_writer_restored_same_endpoint_total 977
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 10577
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 106051324 (101.14 MB)
telemt_user_octets_to_client{user="hello"} 3196741380 (2.98 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 4772.4 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10831
telemt_connections_bad_total 50
telemt_handshake_timeouts_total 207
telemt_upstream_connect_attempt_total 2653
telemt_upstream_connect_success_total 2633
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 2653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 95891
telemt_me_reconnect_success_total 2017
telemt_me_reader_eof_total 2115
telemt_me_idle_close_by_peer_total 2115
telemt_me_route_drop_no_conn_total 4133
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9627
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 2132
telemt_me_refill_failed_total 3045
telemt_me_writer_restored_same_endpoint_total 1979
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 9933
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 447201749 (426.48 MB)
telemt_user_octets_to_client{user="hello"} 5039687722 (4.69 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 4776.9 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15086
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 1225
telemt_upstream_connect_success_total 1219
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 662
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 930
telemt_me_reconnect_success_total 924
telemt_me_reader_eof_total 923
telemt_me_idle_close_by_peer_total 923
telemt_me_route_drop_no_conn_total 7699
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14335
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 173
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 129
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 922
telemt_me_writer_restored_same_endpoint_total 922
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_user_connections_total{user="hello"} 14219
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 179952724 (171.62 MB)
telemt_user_octets_to_client{user="hello"} 5126994832 (4.77 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 4770.0 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10949
telemt_connections_bad_total 1003
telemt_handshake_timeouts_total 135
telemt_upstream_connect_attempt_total 1259
telemt_upstream_connect_success_total 1240
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 700
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 4756
telemt_me_reconnect_success_total 940
telemt_me_reader_eof_total 1034
telemt_me_idle_close_by_peer_total 1034
telemt_me_route_drop_no_conn_total 3739
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9147
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_me_writer_removed_unexpected_total 1054
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 936
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 9143
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 68338160 (65.17 MB)
telemt_user_octets_to_client{user="hello"} 2229377240 (2.08 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 4769.7 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38143
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 311
telemt_upstream_connect_attempt_total 1114
telemt_upstream_connect_success_total 1084
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 1114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 490
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 808
telemt_me_reconnect_success_total 782
telemt_me_reader_eof_total 783
telemt_me_idle_close_by_peer_total 783
telemt_me_route_drop_no_conn_total 18542
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34900
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 780
telemt_me_writer_restored_same_endpoint_total 778
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 34811
telemt_user_connections_current{user="hello"} 562
telemt_user_octets_from_client{user="hello"} 657550000 (627.09 MB)
telemt_user_octets_to_client{user="hello"} 13450273832 (12.53 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 70
```