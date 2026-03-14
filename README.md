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

# Server Metrics 2026-03-14 12:33:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 190806.9 (53h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 756793
telemt_connections_bad_total 36047
telemt_handshake_timeouts_total 14515
telemt_upstream_connect_attempt_total 48344
telemt_upstream_connect_success_total 48104
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 48344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25916
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6340
telemt_me_reconnect_attempts_total 44003
telemt_me_reconnect_success_total 38234
telemt_me_reader_eof_total 40877
telemt_me_idle_close_by_peer_total 40876
telemt_me_route_drop_no_conn_total 248466
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 648941
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2780
telemt_desync_full_logged_total 928
telemt_desync_suppressed_total 1852
telemt_desync_frames_bucket_total{bucket="1_2"} 574
telemt_desync_frames_bucket_total{bucket="3_10"} 1044
telemt_desync_frames_bucket_total{bucket="gt_10"} 1162
telemt_pool_swap_total 173
telemt_me_writer_removed_unexpected_total 38825
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 38214
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 591
telemt_user_connections_total{user="hello"} 648847
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 17947796826 (16.72 GB)
telemt_user_octets_to_client{user="hello"} 310428674228 (289.11 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 190700.0 (52h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 374309
telemt_connections_bad_total 2865
telemt_handshake_timeouts_total 3353
telemt_upstream_connect_attempt_total 158244
telemt_upstream_connect_success_total 156844
telemt_upstream_connect_fail_total 1400
telemt_upstream_connect_attempts_per_request{bucket="1"} 158244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40432
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2526
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1400
telemt_me_keepalive_timeout_total 5719
telemt_me_reconnect_attempts_total 196878
telemt_me_reconnect_success_total 42247
telemt_me_reader_eof_total 48173
telemt_me_idle_close_by_peer_total 48173
telemt_me_route_drop_no_conn_total 129094
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247965
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 47482
telemt_me_refill_failed_total 4824
telemt_me_writer_restored_same_endpoint_total 42229
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5235
telemt_user_connections_total{user="hello"} 352858
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 3576807407 (3.33 GB)
telemt_user_octets_to_client{user="hello"} 113404946654 (105.62 GB)
telemt_user_msgs_from_client{user="hello"} 1713995
telemt_user_msgs_to_client{user="hello"} 9567945
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 190663.5 (52h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 430995
telemt_connections_bad_total 3334
telemt_handshake_timeouts_total 36700
telemt_upstream_connect_attempt_total 50881
telemt_upstream_connect_success_total 50872
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 50881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27409
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4304
telemt_me_reconnect_attempts_total 42600
telemt_me_reconnect_success_total 41277
telemt_me_reader_eof_total 44341
telemt_me_idle_close_by_peer_total 44341
telemt_me_route_drop_no_conn_total 158131
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375486
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 41771
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 41256
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 494
telemt_user_connections_total{user="hello"} 375220
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 16236087018 (15.12 GB)
telemt_user_octets_to_client{user="hello"} 165554633571 (154.18 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 190639.1 (52h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 549491
telemt_connections_bad_total 16783
telemt_handshake_timeouts_total 5343
telemt_upstream_connect_attempt_total 81317
telemt_upstream_connect_success_total 70599
telemt_upstream_connect_fail_total 10718
telemt_upstream_connect_attempts_per_request{bucket="1"} 81317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29201
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 393
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10718
telemt_me_keepalive_timeout_total 5857
telemt_me_reconnect_attempts_total 159113
telemt_me_reconnect_success_total 42069
telemt_me_reader_eof_total 47054
telemt_me_idle_close_by_peer_total 47046
telemt_me_route_drop_no_conn_total 198624
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 471439
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2194
telemt_desync_full_logged_total 642
telemt_desync_suppressed_total 1552
telemt_desync_frames_bucket_total{bucket="1_2"} 509
telemt_desync_frames_bucket_total{bucket="3_10"} 832
telemt_desync_frames_bucket_total{bucket="gt_10"} 853
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 46204
telemt_me_refill_failed_total 3649
telemt_me_writer_restored_same_endpoint_total 42059
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4135
telemt_user_connections_total{user="hello"} 490299
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 10350210303 (9.64 GB)
telemt_user_octets_to_client{user="hello"} 202300930032 (188.41 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 140810.7 (39h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239932
telemt_connections_bad_total 38581
telemt_handshake_timeouts_total 2195
telemt_upstream_connect_attempt_total 49585
telemt_upstream_connect_success_total 49082
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 49585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_keepalive_timeout_total 3138
telemt_me_reconnect_attempts_total 56714
telemt_me_reconnect_success_total 37175
telemt_me_reader_eof_total 39809
telemt_me_idle_close_by_peer_total 39809
telemt_me_route_drop_no_conn_total 73059
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187835
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 854
telemt_desync_full_logged_total 202
telemt_desync_suppressed_total 652
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 391
telemt_desync_frames_bucket_total{bucket="gt_10"} 320
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 38135
telemt_me_refill_failed_total 606
telemt_me_writer_restored_same_endpoint_total 37157
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 960
telemt_user_connections_total{user="hello"} 192591
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 2779454389 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 88640577203 (82.55 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 190595.5 (52h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1113096
telemt_connections_bad_total 37935
telemt_handshake_timeouts_total 27349
telemt_upstream_connect_attempt_total 39687
telemt_upstream_connect_success_total 39480
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 39687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_keepalive_timeout_total 5215
telemt_me_reconnect_attempts_total 34755
telemt_me_reconnect_success_total 30058
telemt_me_reader_eof_total 32230
telemt_me_idle_close_by_peer_total 32227
telemt_me_route_drop_no_conn_total 523876
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1032294
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 178
telemt_me_writer_removed_unexpected_total 30587
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 30051
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 529
telemt_user_connections_total{user="hello"} 1004893
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 21516425984 (20.04 GB)
telemt_user_octets_to_client{user="hello"} 507653442548 (472.79 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 64
```