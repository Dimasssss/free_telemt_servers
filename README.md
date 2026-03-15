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

# Server Metrics 2026-03-15 14:58:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 60237.5 (16h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272645
telemt_connections_bad_total 2641
telemt_handshake_timeouts_total 7715
telemt_upstream_connect_attempt_total 15091
telemt_upstream_connect_success_total 15013
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 15091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8350
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 15393
telemt_me_reconnect_success_total 12012
telemt_me_reader_eof_total 12805
telemt_me_idle_close_by_peer_total 12805
telemt_me_route_drop_no_conn_total 442921
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312426
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1729
telemt_desync_full_logged_total 690
telemt_desync_suppressed_total 1039
telemt_desync_frames_bucket_total{bucket="1_2"} 312
telemt_desync_frames_bucket_total{bucket="3_10"} 678
telemt_desync_frames_bucket_total{bucket="gt_10"} 739
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12241
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 11981
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 251533
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 5575901540 (5.19 GB)
telemt_user_octets_to_client{user="hello"} 214902589496 (200.14 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 60243.6 (16h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101449
telemt_connections_bad_total 2795
telemt_handshake_timeouts_total 9627
telemt_upstream_connect_attempt_total 16612
telemt_upstream_connect_success_total 16612
telemt_upstream_connect_attempts_per_request{bucket="1"} 16612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9317
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 15926
telemt_me_reconnect_success_total 13570
telemt_me_reader_eof_total 14512
telemt_me_idle_close_by_peer_total 14512
telemt_me_route_drop_no_conn_total 42894
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85934
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 13802
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 13554
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 85925
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 1686987388 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 41557528168 (38.70 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 60236.1 (16h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110903
telemt_connections_bad_total 1657
telemt_handshake_timeouts_total 2810
telemt_upstream_connect_attempt_total 17711
telemt_upstream_connect_success_total 17703
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 17711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 22000
telemt_me_reconnect_success_total 14658
telemt_me_reader_eof_total 15747
telemt_me_idle_close_by_peer_total 15747
telemt_me_route_drop_no_conn_total 42229
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95757
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 15020
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 14650
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 95657
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 10272811140 (9.57 GB)
telemt_user_octets_to_client{user="hello"} 55390339036 (51.59 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 60235.7 (16h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146695
telemt_connections_bad_total 799
telemt_handshake_timeouts_total 930
telemt_upstream_connect_attempt_total 14462
telemt_upstream_connect_success_total 14458
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 14462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 11525
telemt_me_reconnect_success_total 11455
telemt_me_reader_eof_total 12190
telemt_me_idle_close_by_peer_total 12190
telemt_me_route_drop_no_conn_total 56977
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134323
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 471
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 319
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 215
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 11589
telemt_me_writer_restored_same_endpoint_total 11444
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 134237
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 2495319056 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 65200500416 (60.72 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 35307.3 (9h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84971
telemt_connections_bad_total 21631
telemt_handshake_timeouts_total 1460
telemt_upstream_connect_attempt_total 11108
telemt_upstream_connect_success_total 11040
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 11108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 103500
telemt_me_reconnect_success_total 9069
telemt_me_reader_eof_total 9486
telemt_me_idle_close_by_peer_total 9486
telemt_me_route_drop_no_conn_total 29160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59934
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 156
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 9093
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 8965
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 60070
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 862418549 (822.47 MB)
telemt_user_octets_to_client{user="hello"} 24061641199 (22.41 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 60235.4 (16h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366979
telemt_connections_bad_total 49252
telemt_handshake_timeouts_total 3061
telemt_upstream_connect_attempt_total 12860
telemt_upstream_connect_success_total 12783
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 12860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 11051
telemt_me_reconnect_success_total 9763
telemt_me_reader_eof_total 10403
telemt_me_idle_close_by_peer_total 10403
telemt_me_route_drop_no_conn_total 171546
telemt_me_route_drop_channel_closed_total 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303810
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
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
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 9896
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 9736
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 301608
telemt_user_connections_current{user="hello"} 649
telemt_user_octets_from_client{user="hello"} 7669264728 (7.14 GB)
telemt_user_octets_to_client{user="hello"} 154250239732 (143.66 GB)
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 72
```