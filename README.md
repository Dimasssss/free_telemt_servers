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

# Server Metrics 2026-03-14 10:46:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 184395.7 (51h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 721037
telemt_connections_bad_total 34228
telemt_handshake_timeouts_total 13882
telemt_upstream_connect_attempt_total 46989
telemt_upstream_connect_success_total 46754
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 46989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25265
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6057
telemt_me_reconnect_attempts_total 42962
telemt_me_reconnect_success_total 37201
telemt_me_reader_eof_total 39780
telemt_me_idle_close_by_peer_total 39779
telemt_me_route_drop_no_conn_total 238380
telemt_me_route_drop_channel_closed_total 38
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 617624
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2447
telemt_desync_full_logged_total 820
telemt_desync_suppressed_total 1627
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 901
telemt_desync_frames_bucket_total{bucket="gt_10"} 1023
telemt_pool_swap_total 167
telemt_me_writer_removed_unexpected_total 37778
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37181
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 617503
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 17463177646 (16.26 GB)
telemt_user_octets_to_client{user="hello"} 296583212208 (276.21 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 184288.7 (51h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359536
telemt_connections_bad_total 2825
telemt_handshake_timeouts_total 3253
telemt_upstream_connect_attempt_total 154554
telemt_upstream_connect_success_total 153197
telemt_upstream_connect_fail_total 1357
telemt_upstream_connect_attempts_per_request{bucket="1"} 154554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38904
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2463
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1357
telemt_me_keepalive_timeout_total 5479
telemt_me_reconnect_attempts_total 189004
telemt_me_reconnect_success_total 40712
telemt_me_reader_eof_total 46421
telemt_me_idle_close_by_peer_total 46421
telemt_me_route_drop_no_conn_total 124122
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236198
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
telemt_me_writer_removed_unexpected_total 45739
telemt_me_refill_failed_total 4627
telemt_me_writer_restored_same_endpoint_total 40695
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5027
telemt_user_connections_total{user="hello"} 339302
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 3470244499 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 108113511663 (100.69 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 184252.3 (51h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 416328
telemt_connections_bad_total 3279
telemt_handshake_timeouts_total 35866
telemt_upstream_connect_attempt_total 48917
telemt_upstream_connect_success_total 48908
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 48917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26454
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3917
telemt_me_reconnect_attempts_total 40994
telemt_me_reconnect_success_total 39686
telemt_me_reader_eof_total 42657
telemt_me_idle_close_by_peer_total 42657
telemt_me_route_drop_no_conn_total 151324
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362431
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
telemt_me_writer_removed_unexpected_total 40163
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 39665
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 477
telemt_user_connections_total{user="hello"} 362158
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 13998014832 (13.04 GB)
telemt_user_octets_to_client{user="hello"} 159060778412 (148.14 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 184227.9 (51h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 526492
telemt_connections_bad_total 16724
telemt_handshake_timeouts_total 5251
telemt_upstream_connect_attempt_total 79425
telemt_upstream_connect_success_total 68743
telemt_upstream_connect_fail_total 10682
telemt_upstream_connect_attempts_per_request{bucket="1"} 79425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28317
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 352
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10682
telemt_me_keepalive_timeout_total 5675
telemt_me_reconnect_attempts_total 152833
telemt_me_reconnect_success_total 40532
telemt_me_reader_eof_total 45337
telemt_me_idle_close_by_peer_total 45329
telemt_me_route_drop_no_conn_total 190783
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 450864
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2017
telemt_desync_full_logged_total 599
telemt_desync_suppressed_total 1418
telemt_desync_frames_bucket_total{bucket="1_2"} 478
telemt_desync_frames_bucket_total{bucket="3_10"} 774
telemt_desync_frames_bucket_total{bucket="gt_10"} 765
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 44501
telemt_me_refill_failed_total 3501
telemt_me_writer_restored_same_endpoint_total 40522
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3969
telemt_user_connections_total{user="hello"} 469731
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 10019455327 (9.33 GB)
telemt_user_octets_to_client{user="hello"} 193646342212 (180.35 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 134399.3 (37h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225060
telemt_connections_bad_total 35054
telemt_handshake_timeouts_total 2002
telemt_upstream_connect_attempt_total 47399
telemt_upstream_connect_success_total 46929
telemt_upstream_connect_fail_total 470
telemt_upstream_connect_attempts_per_request{bucket="1"} 47399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23323
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 470
telemt_me_keepalive_timeout_total 2824
telemt_me_reconnect_attempts_total 51220
telemt_me_reconnect_success_total 35336
telemt_me_reader_eof_total 37806
telemt_me_idle_close_by_peer_total 37806
telemt_me_route_drop_no_conn_total 68088
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177093
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
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 36158
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 35318
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 822
telemt_user_connections_total{user="hello"} 181850
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 2690339733 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 84405332975 (78.61 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 184184.4 (51h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1069019
telemt_connections_bad_total 37170
telemt_handshake_timeouts_total 26961
telemt_upstream_connect_attempt_total 38516
telemt_upstream_connect_success_total 38313
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 38516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_timeout_total 4879
telemt_me_reconnect_attempts_total 33894
telemt_me_reconnect_success_total 29204
telemt_me_reader_eof_total 31308
telemt_me_idle_close_by_peer_total 31305
telemt_me_route_drop_no_conn_total 500948
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 991116
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
telemt_me_writer_removed_unexpected_total 29718
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29197
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 963703
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 18065269712 (16.82 GB)
telemt_user_octets_to_client{user="hello"} 483802197384 (450.58 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 67
```