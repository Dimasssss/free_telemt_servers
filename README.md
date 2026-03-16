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

# Server Metrics 2026-03-16 08:19:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 122719.0 (34h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 570279
telemt_connections_bad_total 5778
telemt_handshake_timeouts_total 20022
telemt_upstream_connect_attempt_total 28657
telemt_upstream_connect_success_total 28522
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 28657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15794
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25879
telemt_me_reconnect_success_total 22444
telemt_me_reader_eof_total 24015
telemt_me_idle_close_by_peer_total 24015
telemt_me_route_drop_no_conn_total 527904
telemt_me_route_drop_channel_closed_total 84
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 566214
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2733
telemt_desync_full_logged_total 1073
telemt_desync_suppressed_total 1660
telemt_desync_frames_bucket_total{bucket="1_2"} 598
telemt_desync_frames_bucket_total{bucket="3_10"} 1048
telemt_desync_frames_bucket_total{bucket="gt_10"} 1087
telemt_pool_swap_total 120
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22800
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 22410
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 505035
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 9647069588 (8.98 GB)
telemt_user_octets_to_client{user="hello"} 320837105324 (298.80 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 122725.6 (34h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229869
telemt_connections_bad_total 3157
telemt_handshake_timeouts_total 15156
telemt_upstream_connect_attempt_total 33060
telemt_upstream_connect_success_total 32985
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 33060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 645
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 35766
telemt_me_reconnect_success_total 26476
telemt_me_reader_eof_total 28401
telemt_me_idle_close_by_peer_total 28400
telemt_me_route_drop_no_conn_total 111695
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203494
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 150
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 27128
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 26460
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 652
telemt_user_connections_total{user="hello"} 203035
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 4613452233 (4.30 GB)
telemt_user_octets_to_client{user="hello"} 114198364160 (106.36 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 122718.0 (34h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245480
telemt_connections_bad_total 5736
telemt_handshake_timeouts_total 4630
telemt_upstream_connect_attempt_total 34129
telemt_upstream_connect_success_total 34121
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 34129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 35371
telemt_me_reconnect_success_total 27964
telemt_me_reader_eof_total 30086
telemt_me_idle_close_by_peer_total 30085
telemt_me_route_drop_no_conn_total 85567
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197174
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
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 28469
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 27956
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 505
telemt_user_connections_total{user="hello"} 196876
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 17522271997 (16.32 GB)
telemt_user_octets_to_client{user="hello"} 113267008032 (105.49 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 122717.5 (34h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343018
telemt_connections_bad_total 1348
telemt_handshake_timeouts_total 2995
telemt_upstream_connect_attempt_total 28498
telemt_upstream_connect_success_total 28465
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 28498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14672
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 22502
telemt_me_reconnect_success_total 22361
telemt_me_reader_eof_total 23875
telemt_me_idle_close_by_peer_total 23874
telemt_me_route_drop_no_conn_total 120284
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316266
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1137
telemt_desync_full_logged_total 390
telemt_desync_suppressed_total 747
telemt_desync_frames_bucket_total{bucket="1_2"} 233
telemt_desync_frames_bucket_total{bucket="3_10"} 484
telemt_desync_frames_bucket_total{bucket="gt_10"} 420
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 22653
telemt_me_writer_restored_same_endpoint_total 22350
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 316156
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 4971412450 (4.63 GB)
telemt_user_octets_to_client{user="hello"} 133571853668 (124.40 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 97788.9 (27h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223246
telemt_connections_bad_total 36346
telemt_handshake_timeouts_total 3726
telemt_upstream_connect_attempt_total 27932
telemt_upstream_connect_success_total 27780
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 27932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 117253
telemt_me_reconnect_success_total 22760
telemt_me_reader_eof_total 24179
telemt_me_idle_close_by_peer_total 24179
telemt_me_route_drop_no_conn_total 69653
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176807
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 559
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 426
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 22948
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 22656
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 176427
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 2378898097 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 73613286043 (68.56 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 122716.8 (34h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 811779
telemt_connections_bad_total 71024
telemt_handshake_timeouts_total 8634
telemt_upstream_connect_attempt_total 25750
telemt_upstream_connect_success_total 25614
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 25750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13322
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 20848
telemt_me_reconnect_success_total 19499
telemt_me_reader_eof_total 20827
telemt_me_idle_close_by_peer_total 20827
telemt_me_route_drop_no_conn_total 645676
telemt_me_route_drop_channel_closed_total 111
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 808310
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
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 19774
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 19472
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 666936
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 14606164700 (13.60 GB)
telemt_user_octets_to_client{user="hello"} 401581240288 (374.00 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 88
```