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

# Server Metrics 2026-03-14 18:05:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 17334.4 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99317
telemt_connections_bad_total 14771
telemt_handshake_timeouts_total 508
telemt_upstream_connect_attempt_total 4151
telemt_upstream_connect_success_total 4149
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2088
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 3249
telemt_me_reconnect_success_total 3217
telemt_me_reader_eof_total 3402
telemt_me_idle_close_by_peer_total 3402
telemt_me_route_drop_no_conn_total 35167
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80012
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 320
telemt_desync_full_logged_total 117
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 123
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3270
telemt_me_writer_restored_same_endpoint_total 3199
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 79940
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 1681663904 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 38686604024 (36.03 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 17332.7 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40020
telemt_connections_bad_total 454
telemt_handshake_timeouts_total 833
telemt_upstream_connect_attempt_total 4753
telemt_upstream_connect_success_total 4717
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 4753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 6360
telemt_me_reconnect_success_total 3786
telemt_me_reader_eof_total 4023
telemt_me_idle_close_by_peer_total 4023
telemt_me_route_drop_no_conn_total 21049
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37296
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 3922
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 3781
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 37281
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 547807056 (522.43 MB)
telemt_user_octets_to_client{user="hello"} 15973669248 (14.88 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 17337.5 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42525
telemt_connections_bad_total 360
telemt_handshake_timeouts_total 1742
telemt_upstream_connect_attempt_total 6507
telemt_upstream_connect_success_total 6439
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 6507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 103048
telemt_me_reconnect_success_total 5190
telemt_me_reader_eof_total 5540
telemt_me_idle_close_by_peer_total 5540
telemt_me_route_drop_no_conn_total 16822
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38057
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5451
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 5152
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 38139
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 2859233617 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 20799945686 (19.37 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 17341.9 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54019
telemt_connections_bad_total 121
telemt_handshake_timeouts_total 341
telemt_upstream_connect_attempt_total 4432
telemt_upstream_connect_success_total 4406
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 4432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 3504
telemt_me_reconnect_success_total 3483
telemt_me_reader_eof_total 3640
telemt_me_idle_close_by_peer_total 3640
telemt_me_route_drop_no_conn_total 24551
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51250
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 432
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 319
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3519
telemt_me_writer_restored_same_endpoint_total 3481
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 51128
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 653509808 (623.24 MB)
telemt_user_octets_to_client{user="hello"} 16559912044 (15.42 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 17335.1 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40048
telemt_connections_bad_total 3360
telemt_handshake_timeouts_total 2040
telemt_upstream_connect_attempt_total 4013
telemt_upstream_connect_success_total 3968
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 4013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 9561
telemt_me_reconnect_success_total 3038
telemt_me_reader_eof_total 3343
telemt_me_idle_close_by_peer_total 3343
telemt_me_route_drop_no_conn_total 13619
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32701
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 157
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3267
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3034
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 32693
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 554881648 (529.18 MB)
telemt_user_octets_to_client{user="hello"} 8601781428 (8.01 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 17334.5 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140633
telemt_connections_bad_total 7135
telemt_handshake_timeouts_total 1701
telemt_upstream_connect_attempt_total 3560
telemt_upstream_connect_success_total 3493
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 3560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 7559
telemt_me_reconnect_success_total 2561
telemt_me_reader_eof_total 2794
telemt_me_idle_close_by_peer_total 2794
telemt_me_route_drop_no_conn_total 73582
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125873
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2742
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2557
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 124535
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 2952638360 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 63955980416 (59.56 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 68
```