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

# Server Metrics 2026-03-13 13:13:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 106783.2 (29h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 438798
telemt_connections_bad_total 3213
telemt_handshake_timeouts_total 8438
telemt_upstream_connect_attempt_total 27039
telemt_upstream_connect_success_total 26912
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 27039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2402
telemt_me_reconnect_attempts_total 25090
telemt_me_reconnect_success_total 21562
telemt_me_reader_eof_total 23026
telemt_me_idle_close_by_peer_total 23025
telemt_me_route_drop_no_conn_total 140155
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 382425
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1292
telemt_desync_full_logged_total 458
telemt_desync_suppressed_total 834
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 475
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 21897
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21546
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 335
telemt_user_connections_total{user="hello"} 382009
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 6995741096 (6.52 GB)
telemt_user_octets_to_client{user="hello"} 166066973328 (154.66 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 106676.0 (29h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204281
telemt_connections_bad_total 1680
telemt_handshake_timeouts_total 1506
telemt_upstream_connect_attempt_total 64884
telemt_upstream_connect_success_total 64164
telemt_upstream_connect_fail_total 719
telemt_upstream_connect_attempts_per_request{bucket="1"} 64883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 617
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 719
telemt_me_keepalive_timeout_total 1386
telemt_me_reconnect_attempts_total 101130
telemt_me_reconnect_success_total 25984
telemt_me_reader_eof_total 29092
telemt_me_idle_close_by_peer_total 29092
telemt_me_route_drop_no_conn_total 79520
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160200
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 28556
telemt_me_refill_failed_total 2344
telemt_me_writer_restored_same_endpoint_total 25967
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2572
telemt_user_connections_total{user="hello"} 192826
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 1979731341 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 63138865918 (58.80 GB)
telemt_user_msgs_from_client{user="hello"} 499233
telemt_user_msgs_to_client{user="hello"} 3520429
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 106639.8 (29h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248529
telemt_connections_bad_total 2073
telemt_handshake_timeouts_total 9211
telemt_upstream_connect_attempt_total 28820
telemt_upstream_connect_success_total 28816
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 28820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15432
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2242
telemt_me_reconnect_attempts_total 24643
telemt_me_reconnect_success_total 23430
telemt_me_reader_eof_total 25103
telemt_me_idle_close_by_peer_total 25103
telemt_me_route_drop_no_conn_total 91175
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 228235
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 23686
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23410
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 256
telemt_user_connections_total{user="hello"} 228150
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 9425385584 (8.78 GB)
telemt_user_octets_to_client{user="hello"} 99191309224 (92.38 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 106615.3 (29h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345700
telemt_connections_bad_total 15024
telemt_handshake_timeouts_total 3409
telemt_upstream_connect_attempt_total 40677
telemt_upstream_connect_success_total 30578
telemt_upstream_connect_fail_total 10099
telemt_upstream_connect_attempts_per_request{bucket="1"} 40677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14914
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10099
telemt_me_keepalive_timeout_total 4120
telemt_me_reconnect_attempts_total 93742
telemt_me_reconnect_success_total 22188
telemt_me_reader_eof_total 25094
telemt_me_idle_close_by_peer_total 25087
telemt_me_route_drop_no_conn_total 123812
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 297321
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1081
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 764
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 410
telemt_desync_frames_bucket_total{bucket="gt_10"} 410
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 24704
telemt_me_refill_failed_total 2231
telemt_me_writer_restored_same_endpoint_total 22178
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2516
telemt_user_connections_total{user="hello"} 300232
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 6044054478 (5.63 GB)
telemt_user_octets_to_client{user="hello"} 113022117489 (105.26 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 56786.8 (15h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84206
telemt_connections_bad_total 11225
telemt_handshake_timeouts_total 1193
telemt_upstream_connect_attempt_total 24106
telemt_upstream_connect_success_total 23911
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 24106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_timeout_total 987
telemt_me_reconnect_attempts_total 26061
telemt_me_reconnect_success_total 16143
telemt_me_reader_eof_total 17321
telemt_me_idle_close_by_peer_total 17321
telemt_me_route_drop_no_conn_total 25036
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64196
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 162
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 16592
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 16125
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 69105
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 607854349 (579.70 MB)
telemt_user_octets_to_client{user="hello"} 19537364103 (18.20 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 106571.8 (29h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 616328
telemt_connections_bad_total 17876
telemt_handshake_timeouts_total 16516
telemt_upstream_connect_attempt_total 22569
telemt_upstream_connect_success_total 22454
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 22569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 2504
telemt_me_reconnect_attempts_total 21765
telemt_me_reconnect_success_total 17142
telemt_me_reader_eof_total 18404
telemt_me_idle_close_by_peer_total 18401
telemt_me_route_drop_no_conn_total 301345
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 588039
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 471
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 17508
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17135
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 366
telemt_user_connections_total{user="hello"} 561088
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 9854724756 (9.18 GB)
telemt_user_octets_to_client{user="hello"} 298440409212 (277.94 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 62
```