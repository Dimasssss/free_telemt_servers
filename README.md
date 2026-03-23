# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-23 05:25:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 116366.9 (32h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4116999
telemt_connections_bad_total 394483
telemt_connections_current 1651
telemt_connections_me_current 1651
telemt_handshake_timeouts_total 136178
telemt_upstream_connect_attempt_total 43321
telemt_upstream_connect_success_total 43320
telemt_upstream_connect_attempts_per_request{bucket="1"} 43320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28090
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 857
telemt_me_reconnect_attempts_total 1497
telemt_me_reconnect_success_total 678
telemt_me_reader_eof_total 698
telemt_me_idle_close_by_peer_total 698
telemt_me_route_drop_no_conn_total 3319374
telemt_me_route_drop_channel_closed_total 1323
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3370117
telemt_me_writer_pick_total{mode="p2c",result="full"} 18
telemt_me_endpoint_quarantine_total 829
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 911
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 13942
telemt_desync_full_logged_total 4435
telemt_desync_suppressed_total 9507
telemt_desync_frames_bucket_total{bucket="1_2"} 3628
telemt_desync_frames_bucket_total{bucket="3_10"} 5169
telemt_desync_frames_bucket_total{bucket="gt_10"} 5145
telemt_pool_swap_total 129
telemt_pool_force_close_total 3944
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 744
telemt_me_draining_writers_reap_progress_total 39704
telemt_me_writer_removed_unexpected_total 672
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2841
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37138
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3879
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35760
telemt_me_writer_teardown_success_total{mode="normal"} 39979
telemt_me_writer_teardown_noop_total 39717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79696
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 431.602601
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79696
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 744
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 608
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 3357558
telemt_user_connections_current{user="hello"} 1651
telemt_user_octets_from_client{user="hello"} 45146413284 (42.05 GB)
telemt_user_octets_to_client{user="hello"} 885475108660 (824.66 GB)
telemt_user_unique_ips_current{user="hello"} 597
telemt_user_unique_ips_recent_window{user="hello"} 489
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 129733.2 (36h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4147132
telemt_connections_bad_total 385694
telemt_connections_current 541
telemt_connections_me_current 541
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 107181
telemt_upstream_connect_attempt_total 80921
telemt_upstream_connect_success_total 79949
telemt_upstream_connect_fail_total 864
telemt_upstream_connect_attempts_per_request{bucket="1"} 80813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35591
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 864
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10941
telemt_me_reconnect_success_total 3907
telemt_me_reader_eof_total 3878
telemt_me_idle_close_by_peer_total 3878
telemt_me_route_drop_no_conn_total 3669252
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3288201
telemt_me_endpoint_quarantine_total 1063
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 55
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 55
telemt_me_single_endpoint_shadow_rotate_total 1020
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 13534
telemt_desync_full_logged_total 7630
telemt_desync_suppressed_total 5904
telemt_desync_frames_bucket_total{bucket="1_2"} 3085
telemt_desync_frames_bucket_total{bucket="3_10"} 5304
telemt_desync_frames_bucket_total{bucket="gt_10"} 5145
telemt_pool_swap_total 123
telemt_pool_force_close_total 3394
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 262
telemt_me_draining_writers_reap_progress_total 54341
telemt_me_writer_removed_unexpected_total 3798
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6868
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51313
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2909
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 485
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50947
telemt_me_writer_teardown_success_total{mode="normal"} 58181
telemt_me_writer_teardown_noop_total 54342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112523
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.946843
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112523
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 262
telemt_me_refill_failed_total 278
telemt_me_writer_restored_same_endpoint_total 3454
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 3302635
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 44389437723 (41.34 GB)
telemt_user_octets_to_client{user="hello"} 831263153849 (774.17 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 204593.0 (56h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16659542
telemt_connections_bad_total 1688956
telemt_connections_current 1568
telemt_connections_me_current 1568
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 407749
telemt_upstream_connect_attempt_total 91976
telemt_upstream_connect_success_total 91869
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 91886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45388
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1732
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3260
telemt_me_reconnect_success_total 1686
telemt_me_reader_eof_total 1647
telemt_me_idle_close_by_peer_total 1645
telemt_me_route_drop_no_conn_total 14112997
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13232541
telemt_me_endpoint_quarantine_total 1392
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1551
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 40
telemt_desync_total 55203
telemt_desync_full_logged_total 17646
telemt_desync_suppressed_total 37557
telemt_desync_frames_bucket_total{bucket="1_2"} 12315
telemt_desync_frames_bucket_total{bucket="3_10"} 21621
telemt_desync_frames_bucket_total{bucket="gt_10"} 21267
telemt_pool_swap_total 222
telemt_pool_force_close_total 7120
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1102
telemt_me_draining_writers_reap_progress_total 70801
telemt_me_writer_removed_unexpected_total 1580
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5945
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65722
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6650
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63681
telemt_me_writer_teardown_success_total{mode="normal"} 71667
telemt_me_writer_teardown_noop_total 70855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142522
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 319.183657
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142522
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1102
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1461
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 13232369
telemt_user_connections_current{user="hello"} 1568
telemt_user_octets_from_client{user="hello"} 200186639669 (186.44 GB)
telemt_user_octets_to_client{user="hello"} 3590560847867 (3.27 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 592
telemt_user_unique_ips_recent_window{user="hello"} 275
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 204594.4 (56h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12172415
telemt_connections_bad_total 1291287
telemt_connections_current 986
telemt_connections_me_current 986
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 352679
telemt_upstream_connect_attempt_total 106345
telemt_upstream_connect_success_total 104933
telemt_upstream_connect_fail_total 899
telemt_upstream_connect_attempts_per_request{bucket="1"} 105832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3808
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 899
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4710
telemt_me_reconnect_success_total 2022
telemt_me_reader_eof_total 1886
telemt_me_idle_close_by_peer_total 1886
telemt_me_route_drop_no_conn_total 4609575
telemt_me_route_drop_channel_closed_total 504
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9001009
telemt_me_endpoint_quarantine_total 1397
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1565
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 39587
telemt_desync_full_logged_total 13335
telemt_desync_suppressed_total 26252
telemt_desync_frames_bucket_total{bucket="1_2"} 9831
telemt_desync_frames_bucket_total{bucket="3_10"} 15203
telemt_desync_frames_bucket_total{bucket="gt_10"} 14553
telemt_pool_swap_total 219
telemt_pool_force_close_total 6468
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 722
telemt_me_draining_writers_reap_progress_total 68859
telemt_me_writer_removed_unexpected_total 1916
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6043
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64595
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5956
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62391
telemt_me_writer_teardown_success_total{mode="normal"} 70638
telemt_me_writer_teardown_noop_total 68884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139522
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.689629
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139522
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 722
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1727
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8938555
telemt_user_connections_current{user="hello"} 986
telemt_user_octets_from_client{user="hello"} 220114830076 (205.00 GB)
telemt_user_octets_to_client{user="hello"} 4028983855067 (3.66 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 204558.5 (56h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11315072
telemt_connections_bad_total 1035268
telemt_connections_current 951
telemt_connections_me_current 951
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 356487
telemt_upstream_connect_attempt_total 90762
telemt_upstream_connect_success_total 89186
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 89391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2373
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5895
telemt_me_reconnect_success_total 2480
telemt_me_reader_eof_total 2226
telemt_me_idle_close_by_peer_total 2225
telemt_me_route_drop_no_conn_total 5378014
telemt_me_route_drop_channel_closed_total 385
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8509012
telemt_me_endpoint_quarantine_total 1449
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1530
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 38678
telemt_desync_full_logged_total 12847
telemt_desync_suppressed_total 25831
telemt_desync_frames_bucket_total{bucket="1_2"} 9766
telemt_desync_frames_bucket_total{bucket="3_10"} 14813
telemt_desync_frames_bucket_total{bucket="gt_10"} 14099
telemt_pool_swap_total 215
telemt_pool_force_close_total 6352
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 763
telemt_me_draining_writers_reap_progress_total 69495
telemt_me_writer_removed_unexpected_total 2372
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6777
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65026
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5781
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63143
telemt_me_writer_teardown_success_total{mode="normal"} 71803
telemt_me_writer_teardown_noop_total 69566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 135516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141369
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.973255
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141369
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 763
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2161
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8500803
telemt_user_connections_current{user="hello"} 951
telemt_user_octets_from_client{user="hello"} 194181115119 (180.85 GB)
telemt_user_octets_to_client{user="hello"} 3526845487417 (3.21 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 74838.6 (20h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11659830
telemt_connections_bad_total 699152
telemt_connections_current 1866
telemt_connections_me_current 1866
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 316495
telemt_upstream_connect_attempt_total 67465
telemt_upstream_connect_success_total 63886
telemt_upstream_connect_fail_total 2314
telemt_upstream_connect_attempts_per_request{bucket="1"} 66200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23064
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6052
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2314
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8409
telemt_me_reconnect_success_total 1556
telemt_me_reader_eof_total 982
telemt_me_idle_close_by_peer_total 981
telemt_me_route_drop_no_conn_total 25372628
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9641511
telemt_me_endpoint_quarantine_total 587
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 213
telemt_me_single_endpoint_outage_reconnect_success_total 56
telemt_me_single_endpoint_quarantine_bypass_total 213
telemt_me_single_endpoint_shadow_rotate_total 604
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 17288
telemt_desync_full_logged_total 4814
telemt_desync_suppressed_total 12474
telemt_desync_frames_bucket_total{bucket="1_2"} 3345
telemt_desync_frames_bucket_total{bucket="3_10"} 7068
telemt_desync_frames_bucket_total{bucket="gt_10"} 6875
telemt_pool_swap_total 77
telemt_pool_force_close_total 2384
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 529
telemt_me_draining_writers_reap_progress_total 24849
telemt_me_writer_removed_unexpected_total 1439
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3222
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23018
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2042
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 342
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22465
telemt_me_writer_teardown_success_total{mode="normal"} 26240
telemt_me_writer_teardown_noop_total 24868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51108
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.950229
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51108
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 529
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 997
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 424
telemt_user_connections_total{user="hello"} 9669061
telemt_user_connections_current{user="hello"} 1866
telemt_user_octets_from_client{user="hello"} 90747769971 (84.52 GB)
telemt_user_octets_to_client{user="hello"} 722265515565 (672.66 GB)
telemt_user_msgs_from_client{user="hello"} 71666
telemt_user_msgs_to_client{user="hello"} 62721
telemt_user_unique_ips_current{user="hello"} 669
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 204565.1 (56h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11281798
telemt_connections_bad_total 992155
telemt_connections_current 1202
telemt_connections_me_current 1202
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 252772
telemt_upstream_connect_attempt_total 119663
telemt_upstream_connect_success_total 118421
telemt_upstream_connect_fail_total 1065
telemt_upstream_connect_attempts_per_request{bucket="1"} 119486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47353
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1378
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1065
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73528
telemt_me_reconnect_success_total 3259
telemt_me_reader_eof_total 2954
telemt_me_idle_close_by_peer_total 2951
telemt_me_route_drop_no_conn_total 5319866
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8882685
telemt_me_endpoint_quarantine_total 1391
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1555
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 47320
telemt_desync_full_logged_total 16271
telemt_desync_suppressed_total 31049
telemt_desync_frames_bucket_total{bucket="1_2"} 9621
telemt_desync_frames_bucket_total{bucket="3_10"} 18142
telemt_desync_frames_bucket_total{bucket="gt_10"} 19557
telemt_pool_swap_total 211
telemt_pool_force_close_total 6073
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 684
telemt_me_draining_writers_reap_progress_total 73531
telemt_me_writer_removed_unexpected_total 2971
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7314
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69235
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5324
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67458
telemt_me_writer_teardown_success_total{mode="normal"} 76549
telemt_me_writer_teardown_noop_total 73532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 147925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 149345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 149764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 150037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 150071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 150074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 150074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 150077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 150081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 150081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 150081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 150081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 150081
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.363670
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 150081
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 684
telemt_me_refill_failed_total 4322
telemt_me_writer_restored_same_endpoint_total 2744
telemt_me_writer_restored_fallback_total 56
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 8885318
telemt_user_connections_current{user="hello"} 1202
telemt_user_octets_from_client{user="hello"} 199104318521 (185.43 GB)
telemt_user_octets_to_client{user="hello"} 3400075844424 (3.09 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 141401.4 (39h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12066095
telemt_connections_bad_total 493576
telemt_connections_current 1184
telemt_connections_me_current 1184
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4871276
telemt_upstream_connect_attempt_total 68663
telemt_upstream_connect_success_total 68173
telemt_upstream_connect_fail_total 477
telemt_upstream_connect_attempts_per_request{bucket="1"} 68650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 477
telemt_me_reconnect_attempts_total 49363
telemt_me_reconnect_success_total 1965
telemt_me_reader_eof_total 1650
telemt_me_idle_close_by_peer_total 1649
telemt_me_route_drop_no_conn_total 4142315
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5796341
telemt_me_endpoint_quarantine_total 977
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1090
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32625
telemt_desync_full_logged_total 11160
telemt_desync_suppressed_total 21465
telemt_desync_frames_bucket_total{bucket="1_2"} 6556
telemt_desync_frames_bucket_total{bucket="3_10"} 12847
telemt_desync_frames_bucket_total{bucket="gt_10"} 13222
telemt_pool_swap_total 151
telemt_pool_force_close_total 4240
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 393
telemt_me_draining_writers_reap_progress_total 53452
telemt_me_writer_removed_unexpected_total 1687
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4219
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50977
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3796
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49212
telemt_me_writer_teardown_success_total{mode="normal"} 55196
telemt_me_writer_teardown_noop_total 53459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108655
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.833865
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108655
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 393
telemt_me_refill_failed_total 2753
telemt_me_writer_restored_same_endpoint_total 1735
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5788211
telemt_user_connections_current{user="hello"} 1184
telemt_user_octets_from_client{user="hello"} 121765844660 (113.40 GB)
telemt_user_octets_to_client{user="hello"} 2253073693458 (2.05 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 545
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 122372.0 (33h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1691486
telemt_connections_bad_total 37504
telemt_connections_current 866
telemt_connections_me_current 866
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 36093
telemt_upstream_connect_attempt_total 57596
telemt_upstream_connect_success_total 57416
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 57567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29369
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 838
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 2506
telemt_me_reconnect_success_total 1011
telemt_me_reader_eof_total 1009
telemt_me_idle_close_by_peer_total 1009
telemt_me_route_drop_no_conn_total 565303
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1502503
telemt_me_endpoint_quarantine_total 1038
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1010
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 10353
telemt_desync_full_logged_total 2929
telemt_desync_suppressed_total 7424
telemt_desync_frames_bucket_total{bucket="1_2"} 3261
telemt_desync_frames_bucket_total{bucket="3_10"} 3877
telemt_desync_frames_bucket_total{bucket="gt_10"} 3215
telemt_pool_swap_total 132
telemt_pool_force_close_total 3332
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 178
telemt_me_draining_writers_reap_progress_total 49120
telemt_me_writer_removed_unexpected_total 970
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3705
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46431
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3244
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45788
telemt_me_writer_teardown_success_total{mode="normal"} 50136
telemt_me_writer_teardown_noop_total 49124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99260
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.687055
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99260
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 178
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 866
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 1498070
telemt_user_connections_current{user="hello"} 866
telemt_user_octets_from_client{user="hello"} 27575423597 (25.68 GB)
telemt_user_octets_to_client{user="hello"} 615266026867 (573.01 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 204569.7 (56h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13561210
telemt_connections_bad_total 1635664
telemt_connections_current 1263
telemt_connections_me_current 1263
telemt_handshake_timeouts_total 397244
telemt_upstream_connect_attempt_total 82538
telemt_upstream_connect_success_total 82172
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 82401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41401
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3246
telemt_me_reconnect_success_total 1623
telemt_me_reader_eof_total 1615
telemt_me_idle_close_by_peer_total 1615
telemt_me_route_drop_no_conn_total 4529696
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10228341
telemt_me_endpoint_quarantine_total 1515
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1556
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 42939
telemt_desync_full_logged_total 14006
telemt_desync_suppressed_total 28933
telemt_desync_frames_bucket_total{bucket="1_2"} 10460
telemt_desync_frames_bucket_total{bucket="3_10"} 15759
telemt_desync_frames_bucket_total{bucket="gt_10"} 16720
telemt_pool_swap_total 227
telemt_pool_force_close_total 5925
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 703
telemt_me_draining_writers_reap_progress_total 74727
telemt_me_writer_removed_unexpected_total 1544
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5743
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70589
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5751
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68802
telemt_me_writer_teardown_success_total{mode="normal"} 76332
telemt_me_writer_teardown_noop_total 74729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 148419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 150169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 150552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 150928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 151048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 151061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 151061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 151061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 151061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 151061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 151061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 151061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 151061
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.991382
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 151061
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 703
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1428
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 10194749
telemt_user_connections_current{user="hello"} 1263
telemt_user_octets_from_client{user="hello"} 197006122444 (183.48 GB)
telemt_user_octets_to_client{user="hello"} 4547433020340 (4.14 TB)
telemt_user_unique_ips_current{user="hello"} 475
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 204566.4 (56h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11878462
telemt_connections_bad_total 1387339
telemt_connections_current 1158
telemt_connections_me_current 1158
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 319970
telemt_upstream_connect_attempt_total 110411
telemt_upstream_connect_success_total 109461
telemt_upstream_connect_fail_total 741
telemt_upstream_connect_attempts_per_request{bucket="1"} 110202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47052
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 741
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11114
telemt_me_reconnect_success_total 2761
telemt_me_reader_eof_total 2566
telemt_me_idle_close_by_peer_total 2565
telemt_me_seq_mismatch_total 107
telemt_me_route_drop_no_conn_total 5696695
telemt_me_route_drop_channel_closed_total 355
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9148593
telemt_me_endpoint_quarantine_total 1693
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1561
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 42558
telemt_desync_full_logged_total 13699
telemt_desync_suppressed_total 28859
telemt_desync_frames_bucket_total{bucket="1_2"} 11061
telemt_desync_frames_bucket_total{bucket="3_10"} 15633
telemt_desync_frames_bucket_total{bucket="gt_10"} 15864
telemt_pool_swap_total 217
telemt_pool_force_close_total 5675
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 75085
telemt_me_writer_removed_unexpected_total 2600
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7156
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70631
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5204
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69410
telemt_me_writer_teardown_success_total{mode="normal"} 77787
telemt_me_writer_teardown_noop_total 75090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 150134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 151954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 152508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 152827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 152877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 152877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 152877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 152877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 152877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 152877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 152877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 152877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 152877
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.839551
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 152877
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 434
telemt_me_writer_restored_same_endpoint_total 2201
telemt_me_writer_restored_fallback_total 142
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 9153018
telemt_user_connections_current{user="hello"} 1158
telemt_user_octets_from_client{user="hello"} 159341786172 (148.40 GB)
telemt_user_octets_to_client{user="hello"} 3582541528662 (3.26 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 165
```