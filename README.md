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

# Server Metrics 2026-03-15 15:44:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 62991.4 (17h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287027
telemt_connections_bad_total 2783
telemt_handshake_timeouts_total 8806
telemt_upstream_connect_attempt_total 15702
telemt_upstream_connect_success_total 15619
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8705
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 15870
telemt_me_reconnect_success_total 12487
telemt_me_reader_eof_total 13299
telemt_me_idle_close_by_peer_total 13299
telemt_me_route_drop_no_conn_total 448009
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 325142
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1756
telemt_desync_full_logged_total 702
telemt_desync_suppressed_total 1054
telemt_desync_frames_bucket_total{bucket="1_2"} 316
telemt_desync_frames_bucket_total{bucket="3_10"} 693
telemt_desync_frames_bucket_total{bucket="gt_10"} 747
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12723
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 12453
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 264244
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 5708479952 (5.32 GB)
telemt_user_octets_to_client{user="hello"} 222614801236 (207.33 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 62997.9 (17h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109293
telemt_connections_bad_total 2808
telemt_handshake_timeouts_total 10455
telemt_upstream_connect_attempt_total 17320
telemt_upstream_connect_success_total 17320
telemt_upstream_connect_attempts_per_request{bucket="1"} 17320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 16504
telemt_me_reconnect_success_total 14146
telemt_me_reader_eof_total 15118
telemt_me_idle_close_by_peer_total 15118
telemt_me_route_drop_no_conn_total 45144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92756
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
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 14385
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 14130
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 92740
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 1845755432 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 47441882548 (44.18 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 62990.5 (17h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117165
telemt_connections_bad_total 1662
telemt_handshake_timeouts_total 3008
telemt_upstream_connect_attempt_total 18530
telemt_upstream_connect_success_total 18522
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 18530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 22683
telemt_me_reconnect_success_total 15334
telemt_me_reader_eof_total 16470
telemt_me_idle_close_by_peer_total 16470
telemt_me_route_drop_no_conn_total 45259
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101590
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
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 15704
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 15326
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 101488
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 10364250980 (9.65 GB)
telemt_user_octets_to_client{user="hello"} 58920035944 (54.87 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 62990.0 (17h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155256
telemt_connections_bad_total 872
telemt_handshake_timeouts_total 968
telemt_upstream_connect_attempt_total 15132
telemt_upstream_connect_success_total 15126
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 15132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 12064
telemt_me_reconnect_success_total 11991
telemt_me_reader_eof_total 12752
telemt_me_idle_close_by_peer_total 12752
telemt_me_route_drop_no_conn_total 60610
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142535
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 504
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 335
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 12129
telemt_me_writer_restored_same_endpoint_total 11980
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 142448
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 2754985752 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 67564360216 (62.92 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 38061.6 (10h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92857
telemt_connections_bad_total 22251
telemt_handshake_timeouts_total 2147
telemt_upstream_connect_attempt_total 11805
telemt_upstream_connect_success_total 11734
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 11805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 104064
telemt_me_reconnect_success_total 9627
telemt_me_reader_eof_total 10079
telemt_me_idle_close_by_peer_total 10079
telemt_me_route_drop_no_conn_total 31624
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66304
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 159
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 9666
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 9523
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 66440
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 916536981 (874.08 MB)
telemt_user_octets_to_client{user="hello"} 27848550795 (25.94 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 62990.8 (17h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392194
telemt_connections_bad_total 50069
telemt_handshake_timeouts_total 3344
telemt_upstream_connect_attempt_total 13475
telemt_upstream_connect_success_total 13396
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 13475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 11530
telemt_me_reconnect_success_total 10234
telemt_me_reader_eof_total 10891
telemt_me_idle_close_by_peer_total 10891
telemt_me_route_drop_no_conn_total 219470
telemt_me_route_drop_channel_closed_total 50
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 344974
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 307
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10376
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 10207
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 324706
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 8277071656 (7.71 GB)
telemt_user_octets_to_client{user="hello"} 170729203976 (159.00 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 92
```