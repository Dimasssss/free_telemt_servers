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

# Server Metrics 2026-03-16 07:59:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 121492.7 (33h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 560809
telemt_connections_bad_total 5766
telemt_handshake_timeouts_total 19668
telemt_upstream_connect_attempt_total 28389
telemt_upstream_connect_success_total 28256
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 28389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15653
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25700
telemt_me_reconnect_success_total 22265
telemt_me_reader_eof_total 23823
telemt_me_idle_close_by_peer_total 23823
telemt_me_route_drop_no_conn_total 525742
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 557388
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2726
telemt_desync_full_logged_total 1070
telemt_desync_suppressed_total 1656
telemt_desync_frames_bucket_total{bucket="1_2"} 596
telemt_desync_frames_bucket_total{bucket="3_10"} 1047
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 118
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22619
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 22231
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 354
telemt_user_connections_total{user="hello"} 496205
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 9519163752 (8.87 GB)
telemt_user_octets_to_client{user="hello"} 318611012704 (296.73 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 121499.2 (33h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224622
telemt_connections_bad_total 3157
telemt_handshake_timeouts_total 15099
telemt_upstream_connect_attempt_total 32713
telemt_upstream_connect_success_total 32638
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 32713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17888
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 626
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 33142
telemt_me_reconnect_success_total 26222
telemt_me_reader_eof_total 28067
telemt_me_idle_close_by_peer_total 28066
telemt_me_route_drop_no_conn_total 109737
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198436
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 121
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 26794
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 26206
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 197979
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 4536930713 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 111474471016 (103.82 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 121491.7 (33h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242010
telemt_connections_bad_total 5734
telemt_handshake_timeouts_total 4613
telemt_upstream_connect_attempt_total 33688
telemt_upstream_connect_success_total 33680
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 33688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19005
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 35023
telemt_me_reconnect_success_total 27620
telemt_me_reader_eof_total 29737
telemt_me_idle_close_by_peer_total 29736
telemt_me_route_drop_no_conn_total 84272
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193797
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 91
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 28120
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 27612
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 500
telemt_user_connections_total{user="hello"} 193506
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 17503854265 (16.30 GB)
telemt_user_octets_to_client{user="hello"} 112522404484 (104.79 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 121491.3 (33h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334058
telemt_connections_bad_total 1345
telemt_handshake_timeouts_total 2953
telemt_upstream_connect_attempt_total 28084
telemt_upstream_connect_success_total 28052
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 28084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14459
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 22177
telemt_me_reconnect_success_total 22040
telemt_me_reader_eof_total 23531
telemt_me_idle_close_by_peer_total 23530
telemt_me_route_drop_no_conn_total 117691
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307707
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1091
telemt_desync_full_logged_total 378
telemt_desync_suppressed_total 713
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 464
telemt_desync_frames_bucket_total{bucket="gt_10"} 405
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 22328
telemt_me_writer_restored_same_endpoint_total 22029
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 307586
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 4905939786 (4.57 GB)
telemt_user_octets_to_client{user="hello"} 131404139672 (122.38 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 96562.8 (26h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218764
telemt_connections_bad_total 36098
telemt_handshake_timeouts_total 3622
telemt_upstream_connect_attempt_total 27626
telemt_upstream_connect_success_total 27475
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 27626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 116992
telemt_me_reconnect_success_total 22501
telemt_me_reader_eof_total 23906
telemt_me_idle_close_by_peer_total 23906
telemt_me_route_drop_no_conn_total 68581
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173473
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 525
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 396
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 227
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 22688
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 22397
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 173095
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 2362330653 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 73004540255 (67.99 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 121490.6 (33h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 799065
telemt_connections_bad_total 69708
telemt_handshake_timeouts_total 7659
telemt_upstream_connect_attempt_total 25493
telemt_upstream_connect_success_total 25358
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 25493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13202
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 20679
telemt_me_reconnect_success_total 19331
telemt_me_reader_eof_total 20646
telemt_me_idle_close_by_peer_total 20646
telemt_me_route_drop_no_conn_total 641085
telemt_me_route_drop_channel_closed_total 108
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 798168
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
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 19602
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 19304
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 656800
telemt_user_connections_current{user="hello"} 574
telemt_user_octets_from_client{user="hello"} 14482045092 (13.49 GB)
telemt_user_octets_to_client{user="hello"} 395931655716 (368.74 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 70
```