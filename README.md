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

# Server Metrics 2026-03-16 10:47:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 131598.8 (36h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 686403
telemt_connections_bad_total 38829
telemt_handshake_timeouts_total 22784
telemt_upstream_connect_attempt_total 30703
telemt_upstream_connect_success_total 30556
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 30703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16876
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 36824
telemt_me_reconnect_success_total 24007
telemt_me_reader_eof_total 25881
telemt_me_idle_close_by_peer_total 25881
telemt_me_route_drop_no_conn_total 593452
telemt_me_route_drop_channel_closed_total 88
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 646075
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2955
telemt_desync_full_logged_total 1145
telemt_desync_suppressed_total 1810
telemt_desync_frames_bucket_total{bucket="1_2"} 653
telemt_desync_frames_bucket_total{bucket="3_10"} 1130
telemt_desync_frames_bucket_total{bucket="gt_10"} 1172
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24665
telemt_me_refill_failed_total 396
telemt_me_writer_restored_same_endpoint_total 23972
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 658
telemt_user_connections_total{user="hello"} 582619
telemt_user_connections_current{user="hello"} 589
telemt_user_octets_from_client{user="hello"} 11122605372 (10.36 GB)
telemt_user_octets_to_client{user="hello"} 348765048704 (324.81 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 131606.6 (36h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274547
telemt_connections_bad_total 3798
telemt_handshake_timeouts_total 15713
telemt_upstream_connect_attempt_total 35153
telemt_upstream_connect_success_total 35078
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 35153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19220
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 722
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 38442
telemt_me_reconnect_success_total 28114
telemt_me_reader_eof_total 30160
telemt_me_idle_close_by_peer_total 30159
telemt_me_route_drop_no_conn_total 129329
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245643
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 210
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 142
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 89
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 28833
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 28098
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 719
telemt_user_connections_total{user="hello"} 245168
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 5274469557 (4.91 GB)
telemt_user_octets_to_client{user="hello"} 129747465224 (120.84 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 131598.8 (36h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278477
telemt_connections_bad_total 5787
telemt_handshake_timeouts_total 7023
telemt_upstream_connect_attempt_total 36644
telemt_upstream_connect_success_total 36636
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 36644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20721
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 37437
telemt_me_reconnect_success_total 30010
telemt_me_reader_eof_total 32237
telemt_me_idle_close_by_peer_total 32236
telemt_me_route_drop_no_conn_total 96236
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226460
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
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 30540
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 30002
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 530
telemt_user_connections_total{user="hello"} 226113
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 17834618025 (16.61 GB)
telemt_user_octets_to_client{user="hello"} 124310805388 (115.77 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 131598.5 (36h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410381
telemt_connections_bad_total 1421
telemt_handshake_timeouts_total 3885
telemt_upstream_connect_attempt_total 30323
telemt_upstream_connect_success_total 30282
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 30323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15511
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 28708
telemt_me_reconnect_success_total 23714
telemt_me_reader_eof_total 25427
telemt_me_idle_close_by_peer_total 25426
telemt_me_route_drop_no_conn_total 142166
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 380325
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1400
telemt_desync_full_logged_total 470
telemt_desync_suppressed_total 930
telemt_desync_frames_bucket_total{bucket="1_2"} 282
telemt_desync_frames_bucket_total{bucket="3_10"} 595
telemt_desync_frames_bucket_total{bucket="gt_10"} 523
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 24187
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 23703
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 473
telemt_user_connections_total{user="hello"} 380194
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 6179267310 (5.75 GB)
telemt_user_octets_to_client{user="hello"} 148559397072 (138.36 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 106669.8 (29h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257764
telemt_connections_bad_total 44107
telemt_handshake_timeouts_total 4346
telemt_upstream_connect_attempt_total 30336
telemt_upstream_connect_success_total 30171
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 30336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 119201
telemt_me_reconnect_success_total 24692
telemt_me_reader_eof_total 26218
telemt_me_idle_close_by_peer_total 26218
telemt_me_route_drop_no_conn_total 78990
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 201591
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 668
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 511
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 302
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 24900
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 24588
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 201203
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 2581610857 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 89430737719 (83.29 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 131597.6 (36h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 913700
telemt_connections_bad_total 73440
telemt_handshake_timeouts_total 10767
telemt_upstream_connect_attempt_total 27695
telemt_upstream_connect_success_total 27548
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 27695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14444
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 23584
telemt_me_reconnect_success_total 20975
telemt_me_reader_eof_total 22392
telemt_me_idle_close_by_peer_total 22392
telemt_me_route_drop_no_conn_total 683946
telemt_me_route_drop_channel_closed_total 124
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 897985
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 462
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 325
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 150
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 21304
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 20948
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 756603
telemt_user_connections_current{user="hello"} 763
telemt_user_octets_from_client{user="hello"} 16005679668 (14.91 GB)
telemt_user_octets_to_client{user="hello"} 444730139508 (414.19 GB)
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 106
```