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

# Server Metrics 2026-03-12 15:52:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 29943.6 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 159112
telemt_connections_bad_total 2022
telemt_handshake_timeouts_total 4745
telemt_upstream_connect_attempt_total 7232
telemt_upstream_connect_success_total 7205
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 7232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3961
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 282
telemt_me_reconnect_attempts_total 5687
telemt_me_reconnect_success_total 5646
telemt_me_reader_eof_total 5946
telemt_me_idle_close_by_peer_total 5945
telemt_me_route_drop_no_conn_total 45890
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137001
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 601
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 375
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5699
telemt_me_writer_restored_same_endpoint_total 5630
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 136967
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 2288522320 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 51983588200 (48.41 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 29837.0 (8h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66555
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 486
telemt_upstream_connect_attempt_total 9602
telemt_upstream_connect_success_total 9395
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 9602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 26194
telemt_me_reconnect_success_total 7858
telemt_me_reader_eof_total 8589
telemt_me_idle_close_by_peer_total 8589
telemt_me_route_drop_no_conn_total 29135
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63264
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 8486
telemt_me_refill_failed_total 572
telemt_me_writer_restored_same_endpoint_total 7843
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 63255
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 706534216 (673.80 MB)
telemt_user_octets_to_client{user="hello"} 17904181600 (16.67 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 29800.4 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90601
telemt_connections_bad_total 1435
telemt_handshake_timeouts_total 1824
telemt_upstream_connect_attempt_total 8177
telemt_upstream_connect_success_total 8177
telemt_upstream_connect_attempts_per_request{bucket="1"} 8177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4214
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 6654
telemt_me_reconnect_success_total 6597
telemt_me_reader_eof_total 6980
telemt_me_idle_close_by_peer_total 6980
telemt_me_route_drop_no_conn_total 33312
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83574
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
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 6653
telemt_me_writer_restored_same_endpoint_total 6577
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 83548
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 2110246232 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 43588588584 (40.60 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 29776.2 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124299
telemt_connections_bad_total 13035
telemt_handshake_timeouts_total 883
telemt_upstream_connect_attempt_total 7021
telemt_upstream_connect_success_total 6820
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 7020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3672
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 301
telemt_me_reconnect_attempts_total 26500
telemt_me_reconnect_success_total 5294
telemt_me_reader_eof_total 6091
telemt_me_idle_close_by_peer_total 6091
telemt_me_route_drop_no_conn_total 43081
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103875
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 369
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 257
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6018
telemt_me_refill_failed_total 661
telemt_me_writer_restored_same_endpoint_total 5286
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 724
telemt_user_connections_total{user="hello"} 103757
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 2015542480 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 44632252104 (41.57 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 29745.6 (8h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69990
telemt_connections_bad_total 5757
telemt_handshake_timeouts_total 1075
telemt_upstream_connect_attempt_total 33154
telemt_upstream_connect_success_total 32790
telemt_upstream_connect_fail_total 363
telemt_upstream_connect_attempts_per_request{bucket="1"} 33153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 363
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 39663
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4805
telemt_me_idle_close_by_peer_total 4805
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12695
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33932
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4831
telemt_me_refill_failed_total 1127
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1147
telemt_user_connections_total{user="hello"} 61536
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 541916101 (516.81 MB)
telemt_user_octets_to_client{user="hello"} 18650646666 (17.37 GB)
telemt_user_msgs_from_client{user="hello"} 444398
telemt_user_msgs_to_client{user="hello"} 1784150
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 29733.0 (8h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185146
telemt_connections_bad_total 911
telemt_handshake_timeouts_total 1478
telemt_upstream_connect_attempt_total 6234
telemt_upstream_connect_success_total 6201
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 6234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 338
telemt_me_reconnect_attempts_total 5761
telemt_me_reconnect_success_total 4697
telemt_me_reader_eof_total 4963
telemt_me_idle_close_by_peer_total 4962
telemt_me_route_drop_no_conn_total 72045
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177262
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 251
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4788
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4690
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 177218
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 3470904844 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 79595917000 (74.13 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 59
```