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

# Server Metrics 2026-03-15 14:27:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 58399.3 (16h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263058
telemt_connections_bad_total 2441
telemt_handshake_timeouts_total 6322
telemt_upstream_connect_attempt_total 14744
telemt_upstream_connect_success_total 14668
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 14744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 15135
telemt_me_reconnect_success_total 11755
telemt_me_reader_eof_total 12533
telemt_me_idle_close_by_peer_total 12533
telemt_me_route_drop_no_conn_total 439153
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305027
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1702
telemt_desync_full_logged_total 676
telemt_desync_suppressed_total 1026
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 734
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11980
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 11724
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 244134
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 5366843816 (5.00 GB)
telemt_user_octets_to_client{user="hello"} 212862616312 (198.24 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 58405.7 (16h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97202
telemt_connections_bad_total 2782
telemt_handshake_timeouts_total 9490
telemt_upstream_connect_attempt_total 16055
telemt_upstream_connect_success_total 16055
telemt_upstream_connect_attempts_per_request{bucket="1"} 16055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 15462
telemt_me_reconnect_success_total 13111
telemt_me_reader_eof_total 14029
telemt_me_idle_close_by_peer_total 14029
telemt_me_route_drop_no_conn_total 41290
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81960
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 13339
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 13095
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 81951
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 1614754496 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 39415898968 (36.71 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 58398.4 (16h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106192
telemt_connections_bad_total 1649
telemt_handshake_timeouts_total 2778
telemt_upstream_connect_attempt_total 17330
telemt_upstream_connect_success_total 17321
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 17329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 20365
telemt_me_reconnect_success_total 14367
telemt_me_reader_eof_total 15408
telemt_me_idle_close_by_peer_total 15408
telemt_me_route_drop_no_conn_total 39645
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91257
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 14689
telemt_me_refill_failed_total 185
telemt_me_writer_restored_same_endpoint_total 14359
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 322
telemt_user_connections_total{user="hello"} 91160
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 10148753556 (9.45 GB)
telemt_user_octets_to_client{user="hello"} 53511252328 (49.84 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 58398.2 (16h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139689
telemt_connections_bad_total 790
telemt_handshake_timeouts_total 915
telemt_upstream_connect_attempt_total 13898
telemt_upstream_connect_success_total 13894
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 13898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 11047
telemt_me_reconnect_success_total 10980
telemt_me_reader_eof_total 11684
telemt_me_idle_close_by_peer_total 11684
telemt_me_route_drop_no_conn_total 54208
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127591
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 441
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 303
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 150
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 11107
telemt_me_writer_restored_same_endpoint_total 10969
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 127507
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 2388110052 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 63255975180 (58.91 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 33469.7 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80610
telemt_connections_bad_total 21288
telemt_handshake_timeouts_total 1416
telemt_upstream_connect_attempt_total 10617
telemt_upstream_connect_success_total 10550
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 10617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 103098
telemt_me_reconnect_success_total 8670
telemt_me_reader_eof_total 9068
telemt_me_idle_close_by_peer_total 9068
telemt_me_route_drop_no_conn_total 27237
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56080
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 153
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 8686
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 8566
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 56217
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 842124429 (803.11 MB)
telemt_user_octets_to_client{user="hello"} 22885174491 (21.31 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 58397.5 (16h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 351543
telemt_connections_bad_total 48446
telemt_handshake_timeouts_total 2887
telemt_upstream_connect_attempt_total 12546
telemt_upstream_connect_success_total 12471
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 12546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 10826
telemt_me_reconnect_success_total 9540
telemt_me_reader_eof_total 10157
telemt_me_idle_close_by_peer_total 10157
telemt_me_route_drop_no_conn_total 162630
telemt_me_route_drop_channel_closed_total 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289838
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 9668
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 9513
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 287694
telemt_user_connections_current{user="hello"} 586
telemt_user_octets_from_client{user="hello"} 7099618592 (6.61 GB)
telemt_user_octets_to_client{user="hello"} 142563693956 (132.77 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 92
```