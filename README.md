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

# Server Metrics 2026-03-15 22:12:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 86265.1 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392909
telemt_connections_bad_total 5195
telemt_handshake_timeouts_total 13889
telemt_upstream_connect_attempt_total 20587
telemt_upstream_connect_success_total 20486
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 20587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 19615
telemt_me_reconnect_success_total 16210
telemt_me_reader_eof_total 17285
telemt_me_idle_close_by_peer_total 17285
telemt_me_route_drop_no_conn_total 484597
telemt_me_route_drop_channel_closed_total 78
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 420135
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2075
telemt_desync_full_logged_total 813
telemt_desync_suppressed_total 1262
telemt_desync_frames_bucket_total{bucket="1_2"} 397
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 876
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 16491
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 16176
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 359197
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 7966397872 (7.42 GB)
telemt_user_octets_to_client{user="hello"} 272116151144 (253.43 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 86271.2 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164625
telemt_connections_bad_total 2895
telemt_handshake_timeouts_total 13989
telemt_upstream_connect_attempt_total 23505
telemt_upstream_connect_success_total 23430
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 23505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 607
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 25627
telemt_me_reconnect_success_total 18737
telemt_me_reader_eof_total 20039
telemt_me_idle_close_by_peer_total 20038
telemt_me_route_drop_no_conn_total 67184
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140972
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
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 19237
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 18721
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 500
telemt_user_connections_total{user="hello"} 141242
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 2643030393 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 75276277252 (70.11 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 86264.0 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163187
telemt_connections_bad_total 1746
telemt_handshake_timeouts_total 3423
telemt_upstream_connect_attempt_total 24626
telemt_upstream_connect_success_total 24618
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 24626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13908
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 27651
telemt_me_reconnect_success_total 20281
telemt_me_reader_eof_total 21797
telemt_me_idle_close_by_peer_total 21796
telemt_me_route_drop_no_conn_total 64371
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145493
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
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 20709
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 20273
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 145375
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 11101459612 (10.34 GB)
telemt_user_octets_to_client{user="hello"} 90817429808 (84.58 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 86263.8 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237464
telemt_connections_bad_total 1193
telemt_handshake_timeouts_total 1615
telemt_upstream_connect_attempt_total 20090
telemt_upstream_connect_success_total 20071
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 20090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10370
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 15891
telemt_me_reconnect_success_total 15795
telemt_me_reader_eof_total 16828
telemt_me_idle_close_by_peer_total 16828
telemt_me_route_drop_no_conn_total 86972
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218931
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 827
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 538
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 305
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 15981
telemt_me_writer_restored_same_endpoint_total 15784
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 218843
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 4049139080 (3.77 GB)
telemt_user_octets_to_client{user="hello"} 104490021252 (97.31 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 61335.2 (17h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147081
telemt_connections_bad_total 27702
telemt_handshake_timeouts_total 2673
telemt_upstream_connect_attempt_total 17713
telemt_upstream_connect_success_total 17607
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 17713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9538
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 108813
telemt_me_reconnect_success_total 14354
telemt_me_reader_eof_total 15142
telemt_me_idle_close_by_peer_total 15142
telemt_me_route_drop_no_conn_total 47891
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112483
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 14457
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 14250
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 112612
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 1699525189 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 42388710207 (39.48 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 86262.9 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 589227
telemt_connections_bad_total 58569
telemt_handshake_timeouts_total 4429
telemt_upstream_connect_attempt_total 18243
telemt_upstream_connect_success_total 18138
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 18243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9426
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 15145
telemt_me_reconnect_success_total 13831
telemt_me_reader_eof_total 14716
telemt_me_idle_close_by_peer_total 14716
telemt_me_route_drop_no_conn_total 469763
telemt_me_route_drop_channel_closed_total 95
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 604500
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 324
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 14023
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 13804
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 492088
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 12116475956 (11.28 GB)
telemt_user_octets_to_client{user="hello"} 297584610120 (277.15 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 34
```