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

# Server Metrics 2026-03-16 08:04:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 121798.9 (33h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 563228
telemt_connections_bad_total 5766
telemt_handshake_timeouts_total 19860
telemt_upstream_connect_attempt_total 28492
telemt_upstream_connect_success_total 28358
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 28492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15701
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25758
telemt_me_reconnect_success_total 22323
telemt_me_reader_eof_total 23887
telemt_me_idle_close_by_peer_total 23887
telemt_me_route_drop_no_conn_total 526250
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 559526
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2732
telemt_desync_full_logged_total 1072
telemt_desync_suppressed_total 1660
telemt_desync_frames_bucket_total{bucket="1_2"} 597
telemt_desync_frames_bucket_total{bucket="3_10"} 1048
telemt_desync_frames_bucket_total{bucket="gt_10"} 1087
telemt_pool_swap_total 119
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22677
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 22289
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 354
telemt_user_connections_total{user="hello"} 498343
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 9543461732 (8.89 GB)
telemt_user_octets_to_client{user="hello"} 319121309184 (297.20 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 121805.5 (33h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226043
telemt_connections_bad_total 3157
telemt_handshake_timeouts_total 15108
telemt_upstream_connect_attempt_total 32836
telemt_upstream_connect_success_total 32761
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 32836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 635
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 34211
telemt_me_reconnect_success_total 26299
telemt_me_reader_eof_total 28180
telemt_me_idle_close_by_peer_total 28179
telemt_me_route_drop_no_conn_total 110322
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199809
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 126
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 26907
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 26283
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 608
telemt_user_connections_total{user="hello"} 199349
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 4547224029 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 112359645200 (104.64 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 121798.4 (33h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243011
telemt_connections_bad_total 5735
telemt_handshake_timeouts_total 4621
telemt_upstream_connect_attempt_total 33825
telemt_upstream_connect_success_total 33817
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 33825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 35113
telemt_me_reconnect_success_total 27710
telemt_me_reader_eof_total 29827
telemt_me_idle_close_by_peer_total 29826
telemt_me_route_drop_no_conn_total 84651
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194771
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 93
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 28210
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 27702
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 500
telemt_user_connections_total{user="hello"} 194480
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 17509261489 (16.31 GB)
telemt_user_octets_to_client{user="hello"} 112773656696 (105.03 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 121797.8 (33h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336533
telemt_connections_bad_total 1346
telemt_handshake_timeouts_total 2962
telemt_upstream_connect_attempt_total 28228
telemt_upstream_connect_success_total 28196
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 28228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14524
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 22275
telemt_me_reconnect_success_total 22137
telemt_me_reader_eof_total 23631
telemt_me_idle_close_by_peer_total 23630
telemt_me_route_drop_no_conn_total 118410
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 310096
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1099
telemt_desync_full_logged_total 380
telemt_desync_suppressed_total 719
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 468
telemt_desync_frames_bucket_total{bucket="gt_10"} 407
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 22428
telemt_me_writer_restored_same_endpoint_total 22126
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 309974
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 4925684394 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 132340611964 (123.25 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 96869.2 (26h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220506
telemt_connections_bad_total 36156
telemt_handshake_timeouts_total 3723
telemt_upstream_connect_attempt_total 27696
telemt_upstream_connect_success_total 27545
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 27696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 117062
telemt_me_reconnect_success_total 22571
telemt_me_reader_eof_total 23976
telemt_me_idle_close_by_peer_total 23976
telemt_me_route_drop_no_conn_total 68919
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174404
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 545
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 414
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 22758
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 22467
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 174026
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 2367601429 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 73228187651 (68.20 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 121797.1 (33h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 802325
telemt_connections_bad_total 70039
telemt_handshake_timeouts_total 7884
telemt_upstream_connect_attempt_total 25588
telemt_upstream_connect_success_total 25452
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 25588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13247
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 20730
telemt_me_reconnect_success_total 19382
telemt_me_reader_eof_total 20704
telemt_me_idle_close_by_peer_total 20704
telemt_me_route_drop_no_conn_total 642276
telemt_me_route_drop_channel_closed_total 110
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 800830
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
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 19653
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 19355
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 659460
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 14513452980 (13.52 GB)
telemt_user_octets_to_client{user="hello"} 397696390472 (370.38 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 88
```