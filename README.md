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

# Server Metrics 2026-03-12 13:08:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 20125.0 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106696
telemt_connections_bad_total 542
telemt_handshake_timeouts_total 3690
telemt_upstream_connect_attempt_total 4936
telemt_upstream_connect_success_total 4913
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 208
telemt_me_reconnect_attempts_total 3881
telemt_me_reconnect_success_total 3855
telemt_me_reader_eof_total 4034
telemt_me_idle_close_by_peer_total 4033
telemt_me_route_drop_no_conn_total 30124
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95207
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 446
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 279
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3884
telemt_me_writer_restored_same_endpoint_total 3839
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 95172
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 1316540456 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 35211608556 (32.79 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 20018.6 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43322
telemt_connections_bad_total 335
telemt_handshake_timeouts_total 335
telemt_upstream_connect_attempt_total 5956
telemt_upstream_connect_success_total 5802
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 5955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3384
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 147
telemt_me_reconnect_attempts_total 20591
telemt_me_reconnect_success_total 4764
telemt_me_reader_eof_total 5318
telemt_me_idle_close_by_peer_total 5318
telemt_me_route_drop_no_conn_total 18562
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41277
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 5282
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 4749
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 518
telemt_user_connections_total{user="hello"} 41277
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 499338820 (476.21 MB)
telemt_user_octets_to_client{user="hello"} 11085522864 (10.32 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 19981.9 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58570
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 615
telemt_upstream_connect_attempt_total 5457
telemt_upstream_connect_success_total 5457
telemt_upstream_connect_attempts_per_request{bucket="1"} 5457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2768
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 4422
telemt_me_reconnect_success_total 4390
telemt_me_reader_eof_total 4626
telemt_me_idle_close_by_peer_total 4626
telemt_me_route_drop_no_conn_total 20400
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55131
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4414
telemt_me_writer_restored_same_endpoint_total 4370
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 55114
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 1766159720 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 33571818132 (31.27 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 19957.6 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75080
telemt_connections_bad_total 1095
telemt_handshake_timeouts_total 345
telemt_upstream_connect_attempt_total 5527
telemt_upstream_connect_success_total 5383
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 5527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 196
telemt_me_reconnect_attempts_total 11160
telemt_me_reconnect_success_total 4326
telemt_me_reader_eof_total 4668
telemt_me_idle_close_by_peer_total 4668
telemt_me_route_drop_no_conn_total 25195
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68888
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 208
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 134
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4592
telemt_me_refill_failed_total 212
telemt_me_writer_restored_same_endpoint_total 4318
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 266
telemt_user_connections_total{user="hello"} 68889
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 1139120568 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 32293585412 (30.08 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 19927.0 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42879
telemt_connections_bad_total 3763
telemt_handshake_timeouts_total 651
telemt_upstream_connect_attempt_total 11230
telemt_upstream_connect_success_total 10996
telemt_upstream_connect_fail_total 234
telemt_upstream_connect_attempts_per_request{bucket="1"} 11230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3320
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 234
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 24685
telemt_me_reconnect_success_total 3621
telemt_me_reader_eof_total 4276
telemt_me_idle_close_by_peer_total 4276
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 11509
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31052
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 404
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 334
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4300
telemt_me_refill_failed_total 659
telemt_me_writer_restored_same_endpoint_total 3604
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 679
telemt_user_connections_total{user="hello"} 37395
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 279393742 (266.45 MB)
telemt_user_octets_to_client{user="hello"} 9371760811 (8.73 GB)
telemt_user_msgs_from_client{user="hello"} 82005
telemt_user_msgs_to_client{user="hello"} 257684
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 19913.9 (5h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114352
telemt_connections_bad_total 766
telemt_handshake_timeouts_total 952
telemt_upstream_connect_attempt_total 4054
telemt_upstream_connect_success_total 4032
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 4054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2098
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 3018
telemt_me_reconnect_success_total 2991
telemt_me_reader_eof_total 3150
telemt_me_idle_close_by_peer_total 3150
telemt_me_route_drop_no_conn_total 46817
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108873
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 210
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3030
telemt_me_writer_restored_same_endpoint_total 2984
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 108838
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 2593110200 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 49087421016 (45.72 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 59
```