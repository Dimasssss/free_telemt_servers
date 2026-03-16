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

# Server Metrics 2026-03-16 11:18:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 133443.2 (37h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 720985
telemt_connections_bad_total 53848
telemt_handshake_timeouts_total 23132
telemt_upstream_connect_attempt_total 30939
telemt_upstream_connect_success_total 30791
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 30939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17003
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 38376
telemt_me_reconnect_success_total 24150
telemt_me_reader_eof_total 26075
telemt_me_idle_close_by_peer_total 26075
telemt_me_route_drop_no_conn_total 598188
telemt_me_route_drop_channel_closed_total 90
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 664498
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3069
telemt_desync_full_logged_total 1175
telemt_desync_suppressed_total 1894
telemt_desync_frames_bucket_total{bucket="1_2"} 668
telemt_desync_frames_bucket_total{bucket="3_10"} 1206
telemt_desync_frames_bucket_total{bucket="gt_10"} 1195
telemt_pool_swap_total 122
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24854
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 24115
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 704
telemt_user_connections_total{user="hello"} 601029
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 11539983216 (10.75 GB)
telemt_user_octets_to_client{user="hello"} 354374739120 (330.04 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 133450.6 (37h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290931
telemt_connections_bad_total 3805
telemt_handshake_timeouts_total 18401
telemt_upstream_connect_attempt_total 35812
telemt_upstream_connect_success_total 35705
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 35812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19434
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 824
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1679
telemt_me_reconnect_attempts_total 38791
telemt_me_reconnect_success_total 28440
telemt_me_reader_eof_total 30485
telemt_me_idle_close_by_peer_total 30484
telemt_me_route_drop_no_conn_total 140464
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257449
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
telemt_me_writer_removed_unexpected_total 29167
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 28424
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 727
telemt_user_connections_total{user="hello"} 257162
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 5341610197 (4.97 GB)
telemt_user_octets_to_client{user="hello"} 132022649624 (122.96 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 133443.0 (37h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286596
telemt_connections_bad_total 5914
telemt_handshake_timeouts_total 7583
telemt_upstream_connect_attempt_total 37195
telemt_upstream_connect_success_total 37187
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 37195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21044
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 37899
telemt_me_reconnect_success_total 30466
telemt_me_reader_eof_total 32720
telemt_me_idle_close_by_peer_total 32719
telemt_me_route_drop_no_conn_total 98222
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 233665
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
telemt_me_writer_removed_unexpected_total 31005
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 30458
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 539
telemt_user_connections_total{user="hello"} 233304
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 18782069633 (17.49 GB)
telemt_user_octets_to_client{user="hello"} 126483006392 (117.80 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 133442.9 (37h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426612
telemt_connections_bad_total 1441
telemt_handshake_timeouts_total 3939
telemt_upstream_connect_attempt_total 30843
telemt_upstream_connect_success_total 30799
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 30843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15742
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 29137
telemt_me_reconnect_success_total 24135
telemt_me_reader_eof_total 25870
telemt_me_idle_close_by_peer_total 25869
telemt_me_route_drop_no_conn_total 146344
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 395556
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1479
telemt_desync_full_logged_total 495
telemt_desync_suppressed_total 984
telemt_desync_frames_bucket_total{bucket="1_2"} 295
telemt_desync_frames_bucket_total{bucket="3_10"} 632
telemt_desync_frames_bucket_total{bucket="gt_10"} 552
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 24616
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 24124
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 481
telemt_user_connections_total{user="hello"} 395421
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 6311382774 (5.88 GB)
telemt_user_octets_to_client{user="hello"} 152594549176 (142.11 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 108514.2 (30h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265334
telemt_connections_bad_total 45108
telemt_handshake_timeouts_total 4372
telemt_upstream_connect_attempt_total 31038
telemt_upstream_connect_success_total 30871
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 31038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 120899
telemt_me_reconnect_success_total 25298
telemt_me_reader_eof_total 26866
telemt_me_idle_close_by_peer_total 26866
telemt_me_route_drop_no_conn_total 81230
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207659
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 696
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 528
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 285
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 25548
telemt_me_refill_failed_total 3067
telemt_me_writer_restored_same_endpoint_total 25194
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 207280
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 2644281569 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 92806010699 (86.43 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 133442.2 (37h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 936079
telemt_connections_bad_total 73496
telemt_handshake_timeouts_total 10979
telemt_upstream_connect_attempt_total 28178
telemt_upstream_connect_success_total 28029
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 28178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14745
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 23974
telemt_me_reconnect_success_total 21358
telemt_me_reader_eof_total 22799
telemt_me_idle_close_by_peer_total 22798
telemt_me_route_drop_no_conn_total 692880
telemt_me_route_drop_channel_closed_total 127
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 919306
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 539
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 381
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 180
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 21694
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 21331
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 336
telemt_user_connections_total{user="hello"} 777918
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 16220160616 (15.11 GB)
telemt_user_octets_to_client{user="hello"} 451419888372 (420.42 GB)
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 111
```