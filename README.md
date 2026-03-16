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

# Server Metrics 2026-03-16 00:35:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 94837.9 (26h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 414421
telemt_connections_bad_total 5355
telemt_handshake_timeouts_total 14225
telemt_upstream_connect_attempt_total 22685
telemt_upstream_connect_success_total 22576
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 22685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12520
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 21274
telemt_me_reconnect_success_total 17863
telemt_me_reader_eof_total 19086
telemt_me_idle_close_by_peer_total 19086
telemt_me_route_drop_no_conn_total 491146
telemt_me_route_drop_channel_closed_total 79
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 440340
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2180
telemt_desync_full_logged_total 869
telemt_desync_suppressed_total 1311
telemt_desync_frames_bucket_total{bucket="1_2"} 424
telemt_desync_frames_bucket_total{bucket="3_10"} 841
telemt_desync_frames_bucket_total{bucket="gt_10"} 915
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 18166
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 17829
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 303
telemt_user_connections_total{user="hello"} 379422
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 8188641692 (7.63 GB)
telemt_user_octets_to_client{user="hello"} 280708523504 (261.43 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 94844.5 (26h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172999
telemt_connections_bad_total 2912
telemt_handshake_timeouts_total 14534
telemt_upstream_connect_attempt_total 25855
telemt_upstream_connect_success_total 25780
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 25855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 27547
telemt_me_reconnect_success_total 20646
telemt_me_reader_eof_total 22101
telemt_me_idle_close_by_peer_total 22100
telemt_me_route_drop_no_conn_total 69930
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148556
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 21164
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 20630
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 518
telemt_user_connections_total{user="hello"} 148818
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 3387411717 (3.15 GB)
telemt_user_octets_to_client{user="hello"} 77873999856 (72.53 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 94836.9 (26h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182640
telemt_connections_bad_total 1870
telemt_handshake_timeouts_total 3558
telemt_upstream_connect_attempt_total 26977
telemt_upstream_connect_success_total 26969
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 26977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 29572
telemt_me_reconnect_success_total 22193
telemt_me_reader_eof_total 23875
telemt_me_idle_close_by_peer_total 23874
telemt_me_route_drop_no_conn_total 67434
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152457
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 22638
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 22185
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 445
telemt_user_connections_total{user="hello"} 152332
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 13107371748 (12.21 GB)
telemt_user_octets_to_client{user="hello"} 98469350592 (91.71 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 94836.6 (26h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252534
telemt_connections_bad_total 1210
telemt_handshake_timeouts_total 1643
telemt_upstream_connect_attempt_total 22191
telemt_upstream_connect_success_total 22171
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 22191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11425
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 17558
telemt_me_reconnect_success_total 17454
telemt_me_reader_eof_total 18611
telemt_me_idle_close_by_peer_total 18611
telemt_me_route_drop_no_conn_total 91148
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 233336
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 874
telemt_desync_full_logged_total 305
telemt_desync_suppressed_total 569
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 375
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 17661
telemt_me_writer_restored_same_endpoint_total 17443
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 233248
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 4114348260 (3.83 GB)
telemt_user_octets_to_client{user="hello"} 107134266292 (99.78 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 69908.1 (19h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161126
telemt_connections_bad_total 29297
telemt_handshake_timeouts_total 2824
telemt_upstream_connect_attempt_total 20050
telemt_upstream_connect_success_total 19936
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 20050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 110751
telemt_me_reconnect_success_total 16290
telemt_me_reader_eof_total 17248
telemt_me_idle_close_by_peer_total 17248
telemt_me_route_drop_no_conn_total 51126
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124506
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
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 16413
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 16186
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 124630
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 1798678737 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 44049453123 (41.02 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 94835.9 (26h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 630514
telemt_connections_bad_total 58657
telemt_handshake_timeouts_total 4869
telemt_upstream_connect_attempt_total 20048
telemt_upstream_connect_success_total 19936
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 20048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 16514
telemt_me_reconnect_success_total 15193
telemt_me_reader_eof_total 16195
telemt_me_idle_close_by_peer_total 16195
telemt_me_route_drop_no_conn_total 576272
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 668470
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
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 15411
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 15166
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 527155
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 12621942864 (11.76 GB)
telemt_user_octets_to_client{user="hello"} 325459062180 (303.11 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 40
```