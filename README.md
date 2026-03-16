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

# Server Metrics 2026-03-16 08:40:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 123946.4 (34h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 582066
telemt_connections_bad_total 7122
telemt_handshake_timeouts_total 20587
telemt_upstream_connect_attempt_total 28843
telemt_upstream_connect_success_total 28707
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 28843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15889
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 26021
telemt_me_reconnect_success_total 22584
telemt_me_reader_eof_total 24162
telemt_me_idle_close_by_peer_total 24162
telemt_me_route_drop_no_conn_total 530432
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 575734
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2761
telemt_desync_full_logged_total 1081
telemt_desync_suppressed_total 1680
telemt_desync_frames_bucket_total{bucket="1_2"} 603
telemt_desync_frames_bucket_total{bucket="3_10"} 1062
telemt_desync_frames_bucket_total{bucket="gt_10"} 1096
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22942
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 22550
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 358
telemt_user_connections_total{user="hello"} 514546
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 10041397416 (9.35 GB)
telemt_user_octets_to_client{user="hello"} 325162041540 (302.83 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 123953.1 (34h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235646
telemt_connections_bad_total 3198
telemt_handshake_timeouts_total 15195
telemt_upstream_connect_attempt_total 33292
telemt_upstream_connect_success_total 33217
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 33292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18248
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 653
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 35954
telemt_me_reconnect_success_total 26665
telemt_me_reader_eof_total 28603
telemt_me_idle_close_by_peer_total 28602
telemt_me_route_drop_no_conn_total 114221
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209048
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 164
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 27319
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 26649
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 654
telemt_user_connections_total{user="hello"} 208586
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 4720713089 (4.40 GB)
telemt_user_octets_to_client{user="hello"} 116937106028 (108.91 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 123945.9 (34h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249321
telemt_connections_bad_total 5740
telemt_handshake_timeouts_total 4641
telemt_upstream_connect_attempt_total 34518
telemt_upstream_connect_success_total 34510
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 34518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 35717
telemt_me_reconnect_success_total 28308
telemt_me_reader_eof_total 30458
telemt_me_idle_close_by_peer_total 30457
telemt_me_route_drop_no_conn_total 87141
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200890
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
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 28818
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 28300
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 200592
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 17551678789 (16.35 GB)
telemt_user_octets_to_client{user="hello"} 114281089640 (106.43 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 123944.5 (34h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350247
telemt_connections_bad_total 1361
telemt_handshake_timeouts_total 3025
telemt_upstream_connect_attempt_total 28673
telemt_upstream_connect_success_total 28639
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 28673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14751
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 22633
telemt_me_reconnect_success_total 22489
telemt_me_reader_eof_total 24010
telemt_me_idle_close_by_peer_total 24009
telemt_me_route_drop_no_conn_total 122388
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323282
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1164
telemt_desync_full_logged_total 404
telemt_desync_suppressed_total 760
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 497
telemt_desync_frames_bucket_total{bucket="gt_10"} 426
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 22783
telemt_me_writer_restored_same_endpoint_total 22478
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 323170
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 5103723322 (4.75 GB)
telemt_user_octets_to_client{user="hello"} 135540159300 (126.23 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 99016.1 (27h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226762
telemt_connections_bad_total 36615
telemt_handshake_timeouts_total 3792
telemt_upstream_connect_attempt_total 28187
telemt_upstream_connect_success_total 28035
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 28187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 117465
telemt_me_reconnect_success_total 22970
telemt_me_reader_eof_total 24402
telemt_me_idle_close_by_peer_total 24402
telemt_me_route_drop_no_conn_total 70854
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179881
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 562
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 427
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 23159
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 22866
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 179500
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 2405396805 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 74165590591 (69.07 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 123945.0 (34h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 825991
telemt_connections_bad_total 72370
telemt_handshake_timeouts_total 9558
telemt_upstream_connect_attempt_total 25944
telemt_upstream_connect_success_total 25808
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 25944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13422
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 20998
telemt_me_reconnect_success_total 19649
telemt_me_reader_eof_total 20986
telemt_me_idle_close_by_peer_total 20986
telemt_me_route_drop_no_conn_total 651253
telemt_me_route_drop_channel_closed_total 113
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 819737
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
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 19926
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 19622
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 678372
telemt_user_connections_current{user="hello"} 611
telemt_user_octets_from_client{user="hello"} 14758516304 (13.74 GB)
telemt_user_octets_to_client{user="hello"} 408998177652 (380.91 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 90
```