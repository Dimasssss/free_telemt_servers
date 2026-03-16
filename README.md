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

# Server Metrics 2026-03-16 04:40:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 109543.0 (30h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 468368
telemt_connections_bad_total 5425
telemt_handshake_timeouts_total 15888
telemt_upstream_connect_attempt_total 26134
telemt_upstream_connect_success_total 26014
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 26134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14453
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 24020
telemt_me_reconnect_success_total 20594
telemt_me_reader_eof_total 22028
telemt_me_idle_close_by_peer_total 22028
telemt_me_route_drop_no_conn_total 504802
telemt_me_route_drop_channel_closed_total 82
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 489418
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2390
telemt_desync_full_logged_total 951
telemt_desync_suppressed_total 1439
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 937
telemt_desync_frames_bucket_total{bucket="gt_10"} 969
telemt_pool_swap_total 105
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20921
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 20560
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 428278
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 8649091672 (8.06 GB)
telemt_user_octets_to_client{user="hello"} 298604760636 (278.10 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 109549.5 (30h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189305
telemt_connections_bad_total 2992
telemt_handshake_timeouts_total 14716
telemt_upstream_connect_attempt_total 29735
telemt_upstream_connect_success_total 29660
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 29735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 30736
telemt_me_reconnect_success_total 23827
telemt_me_reader_eof_total 25536
telemt_me_idle_close_by_peer_total 25535
telemt_me_route_drop_no_conn_total 95967
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164687
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 24376
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 23811
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 549
telemt_user_connections_total{user="hello"} 164234
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 3531650645 (3.29 GB)
telemt_user_octets_to_client{user="hello"} 86725007904 (80.77 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 109542.0 (30h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211247
telemt_connections_bad_total 3654
telemt_handshake_timeouts_total 4153
telemt_upstream_connect_attempt_total 30863
telemt_upstream_connect_success_total 30855
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 30863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 32763
telemt_me_reconnect_success_total 25371
telemt_me_reader_eof_total 27331
telemt_me_idle_close_by_peer_total 27330
telemt_me_route_drop_no_conn_total 74825
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166457
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 25851
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 25363
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 480
telemt_user_connections_total{user="hello"} 166190
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 16466616261 (15.34 GB)
telemt_user_octets_to_client{user="hello"} 103431255960 (96.33 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 109541.8 (30h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275971
telemt_connections_bad_total 1244
telemt_handshake_timeouts_total 1911
telemt_upstream_connect_attempt_total 25616
telemt_upstream_connect_success_total 25590
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 25616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 20290
telemt_me_reconnect_success_total 20167
telemt_me_reader_eof_total 21535
telemt_me_idle_close_by_peer_total 21534
telemt_me_route_drop_no_conn_total 101346
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 254991
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 886
telemt_desync_full_logged_total 316
telemt_desync_suppressed_total 570
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 386
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 20415
telemt_me_writer_restored_same_endpoint_total 20156
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 254879
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 4315109736 (4.02 GB)
telemt_user_octets_to_client{user="hello"} 114505629396 (106.64 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 84613.3 (23h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184511
telemt_connections_bad_total 32087
telemt_handshake_timeouts_total 3242
telemt_upstream_connect_attempt_total 24328
telemt_upstream_connect_success_total 24194
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 24328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 114318
telemt_me_reconnect_success_total 19843
telemt_me_reader_eof_total 21047
telemt_me_idle_close_by_peer_total 21047
telemt_me_route_drop_no_conn_total 58748
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144556
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 20001
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 19739
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 144191
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 2003856657 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 61800744531 (57.56 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 109540.9 (30h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 700923
telemt_connections_bad_total 59326
telemt_handshake_timeouts_total 5272
telemt_upstream_connect_attempt_total 23272
telemt_upstream_connect_success_total 23148
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 23272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12080
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 19034
telemt_me_reconnect_success_total 17700
telemt_me_reader_eof_total 18896
telemt_me_idle_close_by_peer_total 18896
telemt_me_route_drop_no_conn_total 603271
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 720294
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 17946
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 17673
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 578968
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 13208188312 (12.30 GB)
telemt_user_octets_to_client{user="hello"} 358040576296 (333.45 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 51
```