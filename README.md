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

# Server Metrics 2026-03-12 13:03:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 19818.3 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105148
telemt_connections_bad_total 542
telemt_handshake_timeouts_total 3654
telemt_upstream_connect_attempt_total 4817
telemt_upstream_connect_success_total 4795
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 4817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2639
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 208
telemt_me_reconnect_attempts_total 3806
telemt_me_reconnect_success_total 3780
telemt_me_reader_eof_total 3947
telemt_me_idle_close_by_peer_total 3946
telemt_me_route_drop_no_conn_total 29554
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93932
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 443
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 277
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3809
telemt_me_writer_restored_same_endpoint_total 3764
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 93897
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 1307074616 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 34789966156 (32.40 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 19711.5 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42526
telemt_connections_bad_total 335
telemt_handshake_timeouts_total 330
telemt_upstream_connect_attempt_total 5811
telemt_upstream_connect_success_total 5666
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 5811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 147
telemt_me_reconnect_attempts_total 20498
telemt_me_reconnect_success_total 4675
telemt_me_reader_eof_total 5223
telemt_me_idle_close_by_peer_total 5223
telemt_me_route_drop_no_conn_total 18329
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40496
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
telemt_me_writer_removed_unexpected_total 5187
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 4660
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 40496
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 494759544 (471.84 MB)
telemt_user_octets_to_client{user="hello"} 10873288740 (10.13 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 19675.2 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57653
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 604
telemt_upstream_connect_attempt_total 5352
telemt_upstream_connect_success_total 5352
telemt_upstream_connect_attempts_per_request{bucket="1"} 5352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2723
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 4364
telemt_me_reconnect_success_total 4332
telemt_me_reader_eof_total 4568
telemt_me_idle_close_by_peer_total 4568
telemt_me_route_drop_no_conn_total 20035
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54275
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
telemt_me_writer_removed_unexpected_total 4356
telemt_me_writer_restored_same_endpoint_total 4312
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 54258
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 1760399824 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 33319959072 (31.03 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 19650.6 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73981
telemt_connections_bad_total 1083
telemt_handshake_timeouts_total 339
telemt_upstream_connect_attempt_total 5385
telemt_upstream_connect_success_total 5250
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 5385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 195
telemt_me_reconnect_attempts_total 10783
telemt_me_reconnect_success_total 4238
telemt_me_reader_eof_total 4568
telemt_me_idle_close_by_peer_total 4568
telemt_me_route_drop_no_conn_total 24809
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67889
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 207
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 134
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4492
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 4230
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 67890
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 1133199068 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 31934527924 (29.74 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 19620.1 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41898
telemt_connections_bad_total 3709
telemt_handshake_timeouts_total 650
telemt_upstream_connect_attempt_total 10301
telemt_upstream_connect_success_total 10067
telemt_upstream_connect_fail_total 234
telemt_upstream_connect_attempts_per_request{bucket="1"} 10301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3248
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 234
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 24551
telemt_me_reconnect_success_total 3615
telemt_me_reader_eof_total 4266
telemt_me_idle_close_by_peer_total 4266
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 11451
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
telemt_me_writer_removed_unexpected_total 4290
telemt_me_refill_failed_total 655
telemt_me_writer_restored_same_endpoint_total 3598
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 675
telemt_user_connections_total{user="hello"} 36495
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 263383063 (251.18 MB)
telemt_user_octets_to_client{user="hello"} 8845099979 (8.24 GB)
telemt_user_msgs_from_client{user="hello"} 66120
telemt_user_msgs_to_client{user="hello"} 203541
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 19607.0 (5h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112311
telemt_connections_bad_total 765
telemt_handshake_timeouts_total 947
telemt_upstream_connect_attempt_total 3978
telemt_upstream_connect_success_total 3957
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 2985
telemt_me_reconnect_success_total 2958
telemt_me_reader_eof_total 3117
telemt_me_idle_close_by_peer_total 3117
telemt_me_route_drop_no_conn_total 46080
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106904
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 209
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2997
telemt_me_writer_restored_same_endpoint_total 2951
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 106871
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 2577194056 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 48793124160 (45.44 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 55
```