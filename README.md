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

# Server Metrics 2026-03-16 00:45:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 95450.0 (26h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 416250
telemt_connections_bad_total 5357
telemt_handshake_timeouts_total 14246
telemt_upstream_connect_attempt_total 22803
telemt_upstream_connect_success_total 22694
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 22803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12590
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 21374
telemt_me_reconnect_success_total 17963
telemt_me_reader_eof_total 19187
telemt_me_idle_close_by_peer_total 19187
telemt_me_route_drop_no_conn_total 491569
telemt_me_route_drop_channel_closed_total 79
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 442102
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2185
telemt_desync_full_logged_total 874
telemt_desync_suppressed_total 1311
telemt_desync_frames_bucket_total{bucket="1_2"} 425
telemt_desync_frames_bucket_total{bucket="3_10"} 844
telemt_desync_frames_bucket_total{bucket="gt_10"} 916
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 18267
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 17929
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 381173
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 8235020692 (7.67 GB)
telemt_user_octets_to_client{user="hello"} 281150061520 (261.84 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 95456.4 (26h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173455
telemt_connections_bad_total 2912
telemt_handshake_timeouts_total 14535
telemt_upstream_connect_attempt_total 26012
telemt_upstream_connect_success_total 25937
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 26012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14057
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 27679
telemt_me_reconnect_success_total 20779
telemt_me_reader_eof_total 22233
telemt_me_idle_close_by_peer_total 22232
telemt_me_route_drop_no_conn_total 70099
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148997
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 21296
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 20763
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 149258
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 3392274041 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 77905580296 (72.56 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 95449.0 (26h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183138
telemt_connections_bad_total 1870
telemt_handshake_timeouts_total 3563
telemt_upstream_connect_attempt_total 27116
telemt_upstream_connect_success_total 27108
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 27116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 29692
telemt_me_reconnect_success_total 22312
telemt_me_reader_eof_total 23996
telemt_me_idle_close_by_peer_total 23995
telemt_me_route_drop_no_conn_total 67635
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152873
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 22759
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 22304
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 447
telemt_user_connections_total{user="hello"} 152748
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 13108846048 (12.21 GB)
telemt_user_octets_to_client{user="hello"} 98650300888 (91.88 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 95448.8 (26h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253818
telemt_connections_bad_total 1210
telemt_handshake_timeouts_total 1644
telemt_upstream_connect_attempt_total 22300
telemt_upstream_connect_success_total 22280
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 22300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11483
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 17650
telemt_me_reconnect_success_total 17546
telemt_me_reader_eof_total 18706
telemt_me_idle_close_by_peer_total 18706
telemt_me_route_drop_no_conn_total 91459
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234431
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 875
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 569
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 376
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 17756
telemt_me_writer_restored_same_endpoint_total 17535
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 234343
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 4117413848 (3.83 GB)
telemt_user_octets_to_client{user="hello"} 107321296544 (99.95 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 70520.2 (19h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162272
telemt_connections_bad_total 29406
telemt_handshake_timeouts_total 2828
telemt_upstream_connect_attempt_total 20228
telemt_upstream_connect_success_total 20111
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 20228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 110883
telemt_me_reconnect_success_total 16422
telemt_me_reader_eof_total 17394
telemt_me_idle_close_by_peer_total 17394
telemt_me_route_drop_no_conn_total 51354
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125489
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 16546
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 16318
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 125613
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 1809116677 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 44386959895 (41.34 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 95448.0 (26h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 632711
telemt_connections_bad_total 58658
telemt_handshake_timeouts_total 4872
telemt_upstream_connect_attempt_total 20155
telemt_upstream_connect_success_total 20043
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 20155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 16607
telemt_me_reconnect_success_total 15287
telemt_me_reader_eof_total 16289
telemt_me_idle_close_by_peer_total 16289
telemt_me_route_drop_no_conn_total 577036
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 670179
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
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 15505
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 15260
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 528864
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 12638592896 (11.77 GB)
telemt_user_octets_to_client{user="hello"} 326241449616 (303.84 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 39
```