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

# Server Metrics 2026-03-16 11:28:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 134055.6 (37h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 726616
telemt_connections_bad_total 53853
telemt_handshake_timeouts_total 23290
telemt_upstream_connect_attempt_total 30999
telemt_upstream_connect_success_total 30851
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 30999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 38436
telemt_me_reconnect_success_total 24210
telemt_me_reader_eof_total 26135
telemt_me_idle_close_by_peer_total 26135
telemt_me_route_drop_no_conn_total 599836
telemt_me_route_drop_channel_closed_total 91
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 669750
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3112
telemt_desync_full_logged_total 1190
telemt_desync_suppressed_total 1922
telemt_desync_frames_bucket_total{bucket="1_2"} 675
telemt_desync_frames_bucket_total{bucket="3_10"} 1236
telemt_desync_frames_bucket_total{bucket="gt_10"} 1201
telemt_pool_swap_total 122
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24914
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 24175
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 704
telemt_user_connections_total{user="hello"} 606278
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 11574355972 (10.78 GB)
telemt_user_octets_to_client{user="hello"} 356588442320 (332.10 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 134061.7 (37h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294799
telemt_connections_bad_total 3806
telemt_handshake_timeouts_total 19217
telemt_upstream_connect_attempt_total 35985
telemt_upstream_connect_success_total 35878
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 35985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19546
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 826
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1694
telemt_me_reconnect_attempts_total 38964
telemt_me_reconnect_success_total 28613
telemt_me_reader_eof_total 30657
telemt_me_idle_close_by_peer_total 30656
telemt_me_route_drop_no_conn_total 141616
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260517
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 225
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 29340
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 28597
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 727
telemt_user_connections_total{user="hello"} 260229
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 5381470093 (5.01 GB)
telemt_user_octets_to_client{user="hello"} 132616864708 (123.51 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 134054.7 (37h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289138
telemt_connections_bad_total 5925
telemt_handshake_timeouts_total 7804
telemt_upstream_connect_attempt_total 37265
telemt_upstream_connect_success_total 37257
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 37265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 37969
telemt_me_reconnect_success_total 30537
telemt_me_reader_eof_total 32792
telemt_me_idle_close_by_peer_total 32791
telemt_me_route_drop_no_conn_total 99151
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235871
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 31077
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 30529
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 540
telemt_user_connections_total{user="hello"} 235500
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 18792048497 (17.50 GB)
telemt_user_octets_to_client{user="hello"} 127022204736 (118.30 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 134054.4 (37h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 431921
telemt_connections_bad_total 1442
telemt_handshake_timeouts_total 3964
telemt_upstream_connect_attempt_total 30926
telemt_upstream_connect_success_total 30882
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 30926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15795
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 29220
telemt_me_reconnect_success_total 24218
telemt_me_reader_eof_total 25954
telemt_me_idle_close_by_peer_total 25953
telemt_me_route_drop_no_conn_total 147482
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 399557
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1490
telemt_desync_full_logged_total 499
telemt_desync_suppressed_total 991
telemt_desync_frames_bucket_total{bucket="1_2"} 295
telemt_desync_frames_bucket_total{bucket="3_10"} 639
telemt_desync_frames_bucket_total{bucket="gt_10"} 556
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 24700
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 24207
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 482
telemt_user_connections_total{user="hello"} 399420
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 6348017290 (5.91 GB)
telemt_user_octets_to_client{user="hello"} 154044650240 (143.47 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 109125.5 (30h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268507
telemt_connections_bad_total 46014
telemt_handshake_timeouts_total 4375
telemt_upstream_connect_attempt_total 31228
telemt_upstream_connect_success_total 31061
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 31228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 121046
telemt_me_reconnect_success_total 25443
telemt_me_reader_eof_total 27031
telemt_me_idle_close_by_peer_total 27031
telemt_me_route_drop_no_conn_total 81834
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209853
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 700
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 287
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 25693
telemt_me_refill_failed_total 3067
telemt_me_writer_restored_same_endpoint_total 25339
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 209474
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 2760247809 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 93494357299 (87.07 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 134053.8 (37h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 943448
telemt_connections_bad_total 73498
telemt_handshake_timeouts_total 11019
telemt_upstream_connect_attempt_total 28270
telemt_upstream_connect_success_total 28121
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 28270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14809
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 24066
telemt_me_reconnect_success_total 21450
telemt_me_reader_eof_total 22893
telemt_me_idle_close_by_peer_total 22892
telemt_me_route_drop_no_conn_total 696185
telemt_me_route_drop_channel_closed_total 128
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 926431
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 557
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 393
telemt_desync_frames_bucket_total{bucket="1_2"} 178
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 194
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 21788
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 21423
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 338
telemt_user_connections_total{user="hello"} 785038
telemt_user_connections_current{user="hello"} 752
telemt_user_octets_from_client{user="hello"} 16329248316 (15.21 GB)
telemt_user_octets_to_client{user="hello"} 454101574268 (422.92 GB)
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 98
```