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

# Server Metrics 2026-03-14 10:41:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 184090.2 (51h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 719276
telemt_connections_bad_total 34039
telemt_handshake_timeouts_total 13863
telemt_upstream_connect_attempt_total 46961
telemt_upstream_connect_success_total 46726
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 46961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6038
telemt_me_reconnect_attempts_total 42934
telemt_me_reconnect_success_total 37173
telemt_me_reader_eof_total 39753
telemt_me_idle_close_by_peer_total 39752
telemt_me_route_drop_no_conn_total 237919
telemt_me_route_drop_channel_closed_total 38
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 616155
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2427
telemt_desync_full_logged_total 816
telemt_desync_suppressed_total 1611
telemt_desync_frames_bucket_total{bucket="1_2"} 520
telemt_desync_frames_bucket_total{bucket="3_10"} 894
telemt_desync_frames_bucket_total{bucket="gt_10"} 1013
telemt_pool_swap_total 167
telemt_me_writer_removed_unexpected_total 37750
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37153
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 616032
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 17444944282 (16.25 GB)
telemt_user_octets_to_client{user="hello"} 296285324460 (275.94 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 183982.9 (51h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358798
telemt_connections_bad_total 2825
telemt_handshake_timeouts_total 3209
telemt_upstream_connect_attempt_total 154433
telemt_upstream_connect_success_total 153075
telemt_upstream_connect_fail_total 1357
telemt_upstream_connect_attempts_per_request{bucket="1"} 154432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38819
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2463
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1357
telemt_me_keepalive_timeout_total 5478
telemt_me_reconnect_attempts_total 188883
telemt_me_reconnect_success_total 40591
telemt_me_reader_eof_total 46297
telemt_me_idle_close_by_peer_total 46297
telemt_me_route_drop_no_conn_total 123733
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235527
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 45
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
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 45615
telemt_me_refill_failed_total 4627
telemt_me_writer_restored_same_endpoint_total 40574
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5024
telemt_user_connections_total{user="hello"} 338631
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 3464424859 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 107854944547 (100.45 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 183946.4 (51h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415790
telemt_connections_bad_total 3268
telemt_handshake_timeouts_total 35847
telemt_upstream_connect_attempt_total 48868
telemt_upstream_connect_success_total 48859
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 48868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26426
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3916
telemt_me_reconnect_attempts_total 40945
telemt_me_reconnect_success_total 39638
telemt_me_reader_eof_total 42608
telemt_me_idle_close_by_peer_total 42608
telemt_me_route_drop_no_conn_total 151124
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361941
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 137
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 173
telemt_me_writer_removed_unexpected_total 40114
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 39617
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 476
telemt_user_connections_total{user="hello"} 361672
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 13983767768 (13.02 GB)
telemt_user_octets_to_client{user="hello"} 158982805056 (148.06 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 183922.3 (51h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 525488
telemt_connections_bad_total 16713
telemt_handshake_timeouts_total 5235
telemt_upstream_connect_attempt_total 79328
telemt_upstream_connect_success_total 68646
telemt_upstream_connect_fail_total 10682
telemt_upstream_connect_attempts_per_request{bucket="1"} 79328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28262
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 351
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10682
telemt_me_keepalive_timeout_total 5673
telemt_me_reconnect_attempts_total 152736
telemt_me_reconnect_success_total 40434
telemt_me_reader_eof_total 45237
telemt_me_idle_close_by_peer_total 45229
telemt_me_route_drop_no_conn_total 190500
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 449930
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2015
telemt_desync_full_logged_total 597
telemt_desync_suppressed_total 1418
telemt_desync_frames_bucket_total{bucket="1_2"} 478
telemt_desync_frames_bucket_total{bucket="3_10"} 774
telemt_desync_frames_bucket_total{bucket="gt_10"} 763
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 44401
telemt_me_refill_failed_total 3501
telemt_me_writer_restored_same_endpoint_total 40424
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3967
telemt_user_connections_total{user="hello"} 468797
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 10015051235 (9.33 GB)
telemt_user_octets_to_client{user="hello"} 193520412436 (180.23 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 134093.6 (37h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224265
telemt_connections_bad_total 34875
telemt_handshake_timeouts_total 2001
telemt_upstream_connect_attempt_total 47238
telemt_upstream_connect_success_total 46772
telemt_upstream_connect_fail_total 466
telemt_upstream_connect_attempts_per_request{bucket="1"} 47238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 466
telemt_me_keepalive_timeout_total 2820
telemt_me_reconnect_attempts_total 51106
telemt_me_reconnect_success_total 35222
telemt_me_reader_eof_total 37661
telemt_me_idle_close_by_peer_total 37661
telemt_me_route_drop_no_conn_total 67876
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176505
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 762
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 574
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 362
telemt_desync_frames_bucket_total{bucket="gt_10"} 273
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 36044
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 35204
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 822
telemt_user_connections_total{user="hello"} 181262
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 2688481877 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 84261369683 (78.47 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 183878.2 (51h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1066778
telemt_connections_bad_total 37067
telemt_handshake_timeouts_total 26948
telemt_upstream_connect_attempt_total 38458
telemt_upstream_connect_success_total 38255
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 38458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20112
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_timeout_total 4878
telemt_me_reconnect_attempts_total 33836
telemt_me_reconnect_success_total 29146
telemt_me_reader_eof_total 31248
telemt_me_idle_close_by_peer_total 31245
telemt_me_route_drop_no_conn_total 499956
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 989056
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 806
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 540
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 29658
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29139
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 961643
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 18046900788 (16.81 GB)
telemt_user_octets_to_client{user="hello"} 483097540392 (449.92 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 75
```