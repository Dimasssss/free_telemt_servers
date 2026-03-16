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

# Server Metrics 2026-03-16 09:46:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 127925.6 (35h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 620301
telemt_connections_bad_total 10667
telemt_handshake_timeouts_total 21683
telemt_upstream_connect_attempt_total 30061
telemt_upstream_connect_success_total 29919
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 30061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16545
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 29856
telemt_me_reconnect_success_total 23565
telemt_me_reader_eof_total 25234
telemt_me_idle_close_by_peer_total 25234
telemt_me_route_drop_no_conn_total 585368
telemt_me_route_drop_channel_closed_total 86
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 610224
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2898
telemt_desync_full_logged_total 1117
telemt_desync_suppressed_total 1781
telemt_desync_frames_bucket_total{bucket="1_2"} 634
telemt_desync_frames_bucket_total{bucket="3_10"} 1111
telemt_desync_frames_bucket_total{bucket="gt_10"} 1153
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24018
telemt_me_refill_failed_total 193
telemt_me_writer_restored_same_endpoint_total 23531
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 453
telemt_user_connections_total{user="hello"} 546791
telemt_user_connections_current{user="hello"} 565
telemt_user_octets_from_client{user="hello"} 10643862512 (9.91 GB)
telemt_user_octets_to_client{user="hello"} 339784649516 (316.45 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 127932.7 (35h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255888
telemt_connections_bad_total 3729
telemt_handshake_timeouts_total 15536
telemt_upstream_connect_attempt_total 34350
telemt_upstream_connect_success_total 34275
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 34350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18790
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 37816
telemt_me_reconnect_success_total 27498
telemt_me_reader_eof_total 29499
telemt_me_idle_close_by_peer_total 29498
telemt_me_route_drop_no_conn_total 121554
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227768
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 196
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 28204
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 27482
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 706
telemt_user_connections_total{user="hello"} 227304
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 4963602269 (4.62 GB)
telemt_user_octets_to_client{user="hello"} 123967737992 (115.45 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 127925.5 (35h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264140
telemt_connections_bad_total 5758
telemt_handshake_timeouts_total 5980
telemt_upstream_connect_attempt_total 35583
telemt_upstream_connect_success_total 35575
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 35583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 36565
telemt_me_reconnect_success_total 29145
telemt_me_reader_eof_total 31330
telemt_me_idle_close_by_peer_total 31329
telemt_me_route_drop_no_conn_total 91175
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213851
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 100
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 29665
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 29137
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 520
telemt_user_connections_total{user="hello"} 213548
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 17686494489 (16.47 GB)
telemt_user_octets_to_client{user="hello"} 118887898028 (110.72 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 127925.0 (35h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 380112
telemt_connections_bad_total 1394
telemt_handshake_timeouts_total 3475
telemt_upstream_connect_attempt_total 29637
telemt_upstream_connect_success_total 29598
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 29637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15225
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 24526
telemt_me_reconnect_success_total 23219
telemt_me_reader_eof_total 24800
telemt_me_idle_close_by_peer_total 24799
telemt_me_route_drop_no_conn_total 132062
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 351539
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1301
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 853
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 553
telemt_desync_frames_bucket_total{bucket="gt_10"} 487
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 23568
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 23208
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 349
telemt_user_connections_total{user="hello"} 351419
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 5908178370 (5.50 GB)
telemt_user_octets_to_client{user="hello"} 141647078996 (131.92 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 102996.3 (28h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238848
telemt_connections_bad_total 37377
telemt_handshake_timeouts_total 4257
telemt_upstream_connect_attempt_total 29407
telemt_upstream_connect_success_total 29248
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 29407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 118459
telemt_me_reconnect_success_total 23956
telemt_me_reader_eof_total 25443
telemt_me_idle_close_by_peer_total 25443
telemt_me_route_drop_no_conn_total 74811
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190358
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 626
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 483
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 24160
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 23852
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 189973
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 2486634241 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 82470993539 (76.81 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 127924.9 (35h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 869420
telemt_connections_bad_total 72605
telemt_handshake_timeouts_total 10188
telemt_upstream_connect_attempt_total 26878
telemt_upstream_connect_success_total 26736
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 26878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14002
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 22951
telemt_me_reconnect_success_total 20349
telemt_me_reader_eof_total 21742
telemt_me_idle_close_by_peer_total 21742
telemt_me_route_drop_no_conn_total 667241
telemt_me_route_drop_channel_closed_total 118
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 858377
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 356
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 256
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 20671
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 20322
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 322
telemt_user_connections_total{user="hello"} 717029
telemt_user_connections_current{user="hello"} 706
telemt_user_octets_from_client{user="hello"} 15340749620 (14.29 GB)
telemt_user_octets_to_client{user="hello"} 432368799884 (402.67 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 102
```