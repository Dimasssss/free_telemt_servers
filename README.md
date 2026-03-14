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

# Server Metrics 2026-03-14 07:33:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 172795.4 (47h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 662571
telemt_connections_bad_total 32381
telemt_handshake_timeouts_total 13073
telemt_upstream_connect_attempt_total 43976
telemt_upstream_connect_success_total 43754
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 43976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5685
telemt_me_reconnect_attempts_total 39475
telemt_me_reconnect_success_total 34782
telemt_me_reader_eof_total 37190
telemt_me_idle_close_by_peer_total 37189
telemt_me_route_drop_no_conn_total 218907
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 564115
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2118
telemt_desync_full_logged_total 725
telemt_desync_suppressed_total 1393
telemt_desync_frames_bucket_total{bucket="1_2"} 460
telemt_desync_frames_bucket_total{bucket="3_10"} 774
telemt_desync_frames_bucket_total{bucket="gt_10"} 884
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 35300
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 34762
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 518
telemt_user_connections_total{user="hello"} 563998
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 16481106310 (15.35 GB)
telemt_user_octets_to_client{user="hello"} 270880648056 (252.28 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 172688.4 (47h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333737
telemt_connections_bad_total 2328
telemt_handshake_timeouts_total 2570
telemt_upstream_connect_attempt_total 150831
telemt_upstream_connect_success_total 149551
telemt_upstream_connect_fail_total 1280
telemt_upstream_connect_attempts_per_request{bucket="1"} 150831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37027
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2425
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1280
telemt_me_keepalive_timeout_total 4023
telemt_me_reconnect_attempts_total 178249
telemt_me_reconnect_success_total 37658
telemt_me_reader_eof_total 43056
telemt_me_idle_close_by_peer_total 43056
telemt_me_route_drop_no_conn_total 110655
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212867
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
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
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 42405
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 37641
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4747
telemt_user_connections_total{user="hello"} 315973
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 3281790815 (3.06 GB)
telemt_user_octets_to_client{user="hello"} 103299115091 (96.20 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 172652.1 (47h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 390080
telemt_connections_bad_total 3174
telemt_handshake_timeouts_total 35208
telemt_upstream_connect_attempt_total 45563
telemt_upstream_connect_success_total 45554
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 45563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24647
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3490
telemt_me_reconnect_attempts_total 38212
telemt_me_reconnect_success_total 36926
telemt_me_reader_eof_total 39689
telemt_me_idle_close_by_peer_total 39689
telemt_me_route_drop_no_conn_total 140967
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338103
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 37372
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 36905
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 446
telemt_user_connections_total{user="hello"} 337875
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 13561833480 (12.63 GB)
telemt_user_octets_to_client{user="hello"} 135909070020 (126.58 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 172627.7 (47h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 492350
telemt_connections_bad_total 16265
telemt_handshake_timeouts_total 4532
telemt_upstream_connect_attempt_total 75963
telemt_upstream_connect_success_total 65369
telemt_upstream_connect_fail_total 10594
telemt_upstream_connect_attempts_per_request{bucket="1"} 75963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26521
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10594
telemt_me_keepalive_timeout_total 5424
telemt_me_reconnect_attempts_total 143811
telemt_me_reconnect_success_total 37750
telemt_me_reader_eof_total 42285
telemt_me_idle_close_by_peer_total 42277
telemt_me_route_drop_no_conn_total 178421
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 419422
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1792
telemt_desync_full_logged_total 536
telemt_desync_suppressed_total 1256
telemt_desync_frames_bucket_total{bucket="1_2"} 427
telemt_desync_frames_bucket_total{bucket="3_10"} 681
telemt_desync_frames_bucket_total{bucket="gt_10"} 684
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 41494
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 37740
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3744
telemt_user_connections_total{user="hello"} 438300
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 9450633215 (8.80 GB)
telemt_user_octets_to_client{user="hello"} 180034983724 (167.67 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 122799.2 (34h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200154
telemt_connections_bad_total 29550
telemt_handshake_timeouts_total 1739
telemt_upstream_connect_attempt_total 43211
telemt_upstream_connect_success_total 42797
telemt_upstream_connect_fail_total 414
telemt_upstream_connect_attempts_per_request{bucket="1"} 43211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21225
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 414
telemt_me_keepalive_timeout_total 2528
telemt_me_reconnect_attempts_total 45229
telemt_me_reconnect_success_total 31795
telemt_me_reader_eof_total 34044
telemt_me_idle_close_by_peer_total 34044
telemt_me_route_drop_no_conn_total 59684
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158488
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 693
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 524
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 333
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 32509
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 31777
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 714
telemt_user_connections_total{user="hello"} 163237
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 2415903873 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 75881762359 (70.67 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 172583.8 (47h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 989517
telemt_connections_bad_total 36094
telemt_handshake_timeouts_total 26156
telemt_upstream_connect_attempt_total 35773
telemt_upstream_connect_success_total 35584
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 35773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18803
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_timeout_total 4720
telemt_me_reconnect_attempts_total 31738
telemt_me_reconnect_success_total 27057
telemt_me_reader_eof_total 29043
telemt_me_idle_close_by_peer_total 29040
telemt_me_route_drop_no_conn_total 465777
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 916612
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 769
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 27547
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 27050
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 889256
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 15233624548 (14.19 GB)
telemt_user_octets_to_client{user="hello"} 447455267084 (416.73 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 61
```