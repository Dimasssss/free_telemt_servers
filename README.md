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

# Server Metrics 2026-03-23 02:52:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 107177.4 (29h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3668390
telemt_connections_bad_total 349005
telemt_connections_current 1045
telemt_connections_me_current 1045
telemt_handshake_timeouts_total 117239
telemt_upstream_connect_attempt_total 39954
telemt_upstream_connect_success_total 39953
telemt_upstream_connect_attempts_per_request{bucket="1"} 39953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25894
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1420
telemt_me_reconnect_success_total 622
telemt_me_reader_eof_total 639
telemt_me_idle_close_by_peer_total 639
telemt_me_route_drop_no_conn_total 3004660
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3002038
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 756
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 835
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_me_writers_warm_current 32
telemt_desync_total 12925
telemt_desync_full_logged_total 4098
telemt_desync_suppressed_total 8827
telemt_desync_frames_bucket_total{bucket="1_2"} 3433
telemt_desync_frames_bucket_total{bucket="3_10"} 4720
telemt_desync_frames_bucket_total{bucket="gt_10"} 4772
telemt_pool_swap_total 118
telemt_pool_force_close_total 3609
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 670
telemt_me_draining_writers_reap_progress_total 36567
telemt_me_writer_removed_unexpected_total 616
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2602
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34230
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3553
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32958
telemt_me_writer_teardown_success_total{mode="normal"} 36832
telemt_me_writer_teardown_noop_total 36578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73410
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 379.460624
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73410
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 670
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 557
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 2990965
telemt_user_connections_current{user="hello"} 1045
telemt_user_octets_from_client{user="hello"} 42655547400 (39.73 GB)
telemt_user_octets_to_client{user="hello"} 816579469180 (760.50 GB)
telemt_user_unique_ips_current{user="hello"} 460
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 120543.7 (33h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4033537
telemt_connections_bad_total 372364
telemt_connections_current 427
telemt_connections_me_current 427
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 101402
telemt_upstream_connect_attempt_total 74880
telemt_upstream_connect_success_total 73968
telemt_upstream_connect_fail_total 805
telemt_upstream_connect_attempts_per_request{bucket="1"} 74773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32790
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 805
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10415
telemt_me_reconnect_success_total 3721
telemt_me_reader_eof_total 3705
telemt_me_idle_close_by_peer_total 3705
telemt_me_route_drop_no_conn_total 3645475
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3204296
telemt_me_endpoint_quarantine_total 969
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 945
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 13072
telemt_desync_full_logged_total 7342
telemt_desync_suppressed_total 5730
telemt_desync_frames_bucket_total{bucket="1_2"} 2966
telemt_desync_frames_bucket_total{bucket="3_10"} 5130
telemt_desync_frames_bucket_total{bucket="gt_10"} 4976
telemt_pool_swap_total 113
telemt_pool_force_close_total 3180
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 50004
telemt_me_writer_removed_unexpected_total 3632
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6459
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47213
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2722
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46824
telemt_me_writer_teardown_success_total{mode="normal"} 53672
telemt_me_writer_teardown_noop_total 50005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103677
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.667019
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103677
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 3302
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 3217654
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 43321464082 (40.35 GB)
telemt_user_octets_to_client{user="hello"} 798869322894 (744.01 GB)
telemt_user_msgs_from_client{user="hello"} 49767
telemt_user_msgs_to_client{user="hello"} 185105
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 195403.5 (54h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16424592
telemt_connections_bad_total 1667056
telemt_connections_current 1128
telemt_connections_me_current 1128
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 399263
telemt_upstream_connect_attempt_total 87986
telemt_upstream_connect_success_total 87879
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 87896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1725
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3048
telemt_me_reconnect_success_total 1623
telemt_me_reader_eof_total 1571
telemt_me_idle_close_by_peer_total 1569
telemt_me_route_drop_no_conn_total 14058269
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13037669
telemt_me_endpoint_quarantine_total 1315
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1472
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
telemt_me_writers_active_current 43
telemt_desync_total 54117
telemt_desync_full_logged_total 17240
telemt_desync_suppressed_total 36877
telemt_desync_frames_bucket_total{bucket="1_2"} 12070
telemt_desync_frames_bucket_total{bucket="3_10"} 21137
telemt_desync_frames_bucket_total{bucket="gt_10"} 20910
telemt_pool_swap_total 212
telemt_pool_force_close_total 6855
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1069
telemt_me_draining_writers_reap_progress_total 67138
telemt_me_writer_removed_unexpected_total 1510
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5667
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62261
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6385
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60283
telemt_me_writer_teardown_success_total{mode="normal"} 67928
telemt_me_writer_teardown_noop_total 67191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135119
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.937266
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135119
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1069
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1405
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 13037654
telemt_user_connections_current{user="hello"} 1128
telemt_user_octets_from_client{user="hello"} 197767020889 (184.18 GB)
telemt_user_octets_to_client{user="hello"} 3515652123683 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 523
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 195404.9 (54h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11965203
telemt_connections_bad_total 1253460
telemt_connections_current 689
telemt_connections_me_current 689
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 345385
telemt_upstream_connect_attempt_total 102258
telemt_upstream_connect_success_total 100922
telemt_upstream_connect_fail_total 883
telemt_upstream_connect_attempts_per_request{bucket="1"} 101805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 883
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4480
telemt_me_reconnect_success_total 1930
telemt_me_reader_eof_total 1796
telemt_me_idle_close_by_peer_total 1796
telemt_me_route_drop_no_conn_total 4565687
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8868072
telemt_me_endpoint_quarantine_total 1330
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1492
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_active_current 43
telemt_desync_total 39066
telemt_desync_full_logged_total 13158
telemt_desync_suppressed_total 25908
telemt_desync_frames_bucket_total{bucket="1_2"} 9677
telemt_desync_frames_bucket_total{bucket="3_10"} 15002
telemt_desync_frames_bucket_total{bucket="gt_10"} 14387
telemt_pool_swap_total 209
telemt_pool_force_close_total 6205
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 714
telemt_me_draining_writers_reap_progress_total 65244
telemt_me_writer_removed_unexpected_total 1823
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5748
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61178
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5693
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59039
telemt_me_writer_teardown_success_total{mode="normal"} 66926
telemt_me_writer_teardown_noop_total 65269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 131770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132195
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.537965
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132195
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 714
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1653
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 8805787
telemt_user_connections_current{user="hello"} 689
telemt_user_octets_from_client{user="hello"} 218232606152 (203.24 GB)
telemt_user_octets_to_client{user="hello"} 3979124348535 (3.62 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 195368.9 (54h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11121795
telemt_connections_bad_total 992343
telemt_connections_current 534
telemt_connections_me_current 534
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 346182
telemt_upstream_connect_attempt_total 86683
telemt_upstream_connect_success_total 85119
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 85324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41582
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2038
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5796
telemt_me_reconnect_success_total 2417
telemt_me_reader_eof_total 2162
telemt_me_idle_close_by_peer_total 2161
telemt_me_route_drop_no_conn_total 5345400
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8396049
telemt_me_endpoint_quarantine_total 1372
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1452
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 19
telemt_desync_total 38288
telemt_desync_full_logged_total 12693
telemt_desync_suppressed_total 25595
telemt_desync_frames_bucket_total{bucket="1_2"} 9676
telemt_desync_frames_bucket_total{bucket="3_10"} 14657
telemt_desync_frames_bucket_total{bucket="gt_10"} 13955
telemt_pool_swap_total 204
telemt_pool_force_close_total 6100
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 746
telemt_me_draining_writers_reap_progress_total 65766
telemt_me_writer_removed_unexpected_total 2310
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6497
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61513
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5529
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59666
telemt_me_writer_teardown_success_total{mode="normal"} 68010
telemt_me_writer_teardown_noop_total 65837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133847
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.859054
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133847
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 746
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2104
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 8387970
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 193065899415 (179.81 GB)
telemt_user_octets_to_client{user="hello"} 3483062986549 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 65649.1 (18h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11348698
telemt_connections_bad_total 670332
telemt_connections_current 1125
telemt_connections_me_current 1125
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 286444
telemt_upstream_connect_attempt_total 61163
telemt_upstream_connect_success_total 57992
telemt_upstream_connect_fail_total 2055
telemt_upstream_connect_attempts_per_request{bucket="1"} 60047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20730
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6019
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2055
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7886
telemt_me_reconnect_success_total 1334
telemt_me_reader_eof_total 869
telemt_me_idle_close_by_peer_total 868
telemt_me_route_drop_no_conn_total 25306102
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9409868
telemt_me_endpoint_quarantine_total 489
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 526
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 16560
telemt_desync_full_logged_total 4547
telemt_desync_suppressed_total 12013
telemt_desync_frames_bucket_total{bucket="1_2"} 3154
telemt_desync_frames_bucket_total{bucket="3_10"} 6750
telemt_desync_frames_bucket_total{bucket="gt_10"} 6656
telemt_pool_swap_total 67
telemt_pool_force_close_total 2150
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 493
telemt_me_draining_writers_reap_progress_total 21443
telemt_me_writer_removed_unexpected_total 1223
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2778
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19834
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1829
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 321
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19293
telemt_me_writer_teardown_success_total{mode="normal"} 22612
telemt_me_writer_teardown_noop_total 21462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44074
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.009965
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44074
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 493
telemt_me_refill_failed_total 341
telemt_me_writer_restored_same_endpoint_total 878
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 9435713
telemt_user_connections_current{user="hello"} 1125
telemt_user_octets_from_client{user="hello"} 87817140186 (81.79 GB)
telemt_user_octets_to_client{user="hello"} 632686342818 (589.24 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 195375.7 (54h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11075612
telemt_connections_bad_total 966792
telemt_connections_current 865
telemt_connections_me_current 865
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 244299
telemt_upstream_connect_attempt_total 115497
telemt_upstream_connect_success_total 114312
telemt_upstream_connect_fail_total 1010
telemt_upstream_connect_attempts_per_request{bucket="1"} 115322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45052
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1010
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73190
telemt_me_reconnect_success_total 3153
telemt_me_reader_eof_total 2850
telemt_me_idle_close_by_peer_total 2848
telemt_me_route_drop_no_conn_total 5273969
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8727217
telemt_me_endpoint_quarantine_total 1320
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1478
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
telemt_me_writers_active_current 49
telemt_me_writers_warm_current 26
telemt_desync_total 46513
telemt_desync_full_logged_total 15965
telemt_desync_suppressed_total 30548
telemt_desync_frames_bucket_total{bucket="1_2"} 9457
telemt_desync_frames_bucket_total{bucket="3_10"} 17804
telemt_desync_frames_bucket_total{bucket="gt_10"} 19252
telemt_pool_swap_total 200
telemt_pool_force_close_total 5814
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 671
telemt_me_draining_writers_reap_progress_total 69765
telemt_me_writer_removed_unexpected_total 2870
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7039
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65640
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5065
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63951
telemt_me_writer_teardown_success_total{mode="normal"} 72679
telemt_me_writer_teardown_noop_total 69766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 140291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 141709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 142128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 142401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142445
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.308896
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142445
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 671
telemt_me_refill_failed_total 4310
telemt_me_writer_restored_same_endpoint_total 2656
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 8730105
telemt_user_connections_current{user="hello"} 865
telemt_user_octets_from_client{user="hello"} 196435798629 (182.95 GB)
telemt_user_octets_to_client{user="hello"} 3336204216036 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 400
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 132211.9 (36h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11788746
telemt_connections_bad_total 483594
telemt_connections_current 650
telemt_connections_me_current 650
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4779049
telemt_upstream_connect_attempt_total 64110
telemt_upstream_connect_success_total 63645
telemt_upstream_connect_fail_total 452
telemt_upstream_connect_attempts_per_request{bucket="1"} 64097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 452
telemt_me_reconnect_attempts_total 49118
telemt_me_reconnect_success_total 1884
telemt_me_reader_eof_total 1561
telemt_me_idle_close_by_peer_total 1560
telemt_me_route_drop_no_conn_total 4102856
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5664358
telemt_me_endpoint_quarantine_total 903
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1016
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_me_writers_active_current 48
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31860
telemt_desync_full_logged_total 10887
telemt_desync_suppressed_total 20973
telemt_desync_frames_bucket_total{bucket="1_2"} 6356
telemt_desync_frames_bucket_total{bucket="3_10"} 12576
telemt_desync_frames_bucket_total{bucket="gt_10"} 12928
telemt_pool_swap_total 140
telemt_pool_force_close_total 4020
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 381
telemt_me_draining_writers_reap_progress_total 49354
telemt_me_writer_removed_unexpected_total 1606
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3967
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47042
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3579
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45334
telemt_me_writer_teardown_success_total{mode="normal"} 51009
telemt_me_writer_teardown_noop_total 49361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100370
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.729375
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100370
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 381
telemt_me_refill_failed_total 2744
telemt_me_writer_restored_same_endpoint_total 1666
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5656461
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 120296701608 (112.04 GB)
telemt_user_octets_to_client{user="hello"} 2196975010222 (2.00 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 113182.5 (31h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1566510
telemt_connections_bad_total 36943
telemt_connections_current 503
telemt_connections_me_current 503
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32228
telemt_upstream_connect_attempt_total 53624
telemt_upstream_connect_success_total 53457
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 53596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27643
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 802
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2329
telemt_me_reconnect_success_total 958
telemt_me_reader_eof_total 948
telemt_me_idle_close_by_peer_total 948
telemt_me_route_drop_no_conn_total 527217
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1392554
telemt_me_endpoint_quarantine_total 955
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 938
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 9714
telemt_desync_full_logged_total 2758
telemt_desync_suppressed_total 6956
telemt_desync_frames_bucket_total{bucket="1_2"} 2978
telemt_desync_frames_bucket_total{bucket="3_10"} 3671
telemt_desync_frames_bucket_total{bucket="gt_10"} 3065
telemt_pool_swap_total 122
telemt_pool_force_close_total 3079
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 45552
telemt_me_writer_removed_unexpected_total 913
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3455
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43052
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2991
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42473
telemt_me_writer_teardown_success_total{mode="normal"} 46507
telemt_me_writer_teardown_noop_total 45556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92063
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.427022
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92063
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 818
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1388308
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 26395321805 (24.58 GB)
telemt_user_octets_to_client{user="hello"} 587100740879 (546.78 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 195380.1 (54h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13399600
telemt_connections_bad_total 1623346
telemt_connections_current 646
telemt_connections_me_current 646
telemt_handshake_timeouts_total 391444
telemt_upstream_connect_attempt_total 78051
telemt_upstream_connect_success_total 77696
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 77915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39231
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3068
telemt_me_reconnect_success_total 1545
telemt_me_reader_eof_total 1530
telemt_me_idle_close_by_peer_total 1530
telemt_me_route_drop_no_conn_total 4490863
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10090364
telemt_me_endpoint_quarantine_total 1421
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1479
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 29
telemt_desync_total 42308
telemt_desync_full_logged_total 13818
telemt_desync_suppressed_total 28490
telemt_desync_frames_bucket_total{bucket="1_2"} 10285
telemt_desync_frames_bucket_total{bucket="3_10"} 15540
telemt_desync_frames_bucket_total{bucket="gt_10"} 16483
telemt_pool_swap_total 216
telemt_pool_force_close_total 5694
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 684
telemt_me_draining_writers_reap_progress_total 70591
telemt_me_writer_removed_unexpected_total 1465
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5487
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66624
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5520
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64897
telemt_me_writer_teardown_success_total{mode="normal"} 72111
telemt_me_writer_teardown_noop_total 70593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 140085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 141812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 142195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 142571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142704
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.834280
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142704
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 684
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1358
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 10057016
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 195106513084 (181.71 GB)
telemt_user_octets_to_client{user="hello"} 4472487105308 (4.07 TB)
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 195376.8 (54h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11704778
telemt_connections_bad_total 1367879
telemt_connections_current 750
telemt_connections_me_current 750
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 313109
telemt_upstream_connect_attempt_total 105648
telemt_upstream_connect_success_total 104742
telemt_upstream_connect_fail_total 698
telemt_upstream_connect_attempts_per_request{bucket="1"} 105440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44794
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 698
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10681
telemt_me_reconnect_success_total 2644
telemt_me_reader_eof_total 2454
telemt_me_idle_close_by_peer_total 2453
telemt_me_seq_mismatch_total 102
telemt_me_route_drop_no_conn_total 5658444
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9006272
telemt_me_endpoint_quarantine_total 1594
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 53
telemt_me_single_endpoint_outage_exit_total 53
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 1483
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_me_writers_warm_current 27
telemt_desync_total 42042
telemt_desync_full_logged_total 13537
telemt_desync_suppressed_total 28505
telemt_desync_frames_bucket_total{bucket="1_2"} 10890
telemt_desync_frames_bucket_total{bucket="3_10"} 15463
telemt_desync_frames_bucket_total{bucket="gt_10"} 15689
telemt_pool_swap_total 206
telemt_pool_force_close_total 5459
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 672
telemt_me_draining_writers_reap_progress_total 70758
telemt_me_writer_removed_unexpected_total 2494
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6856
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66487
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4988
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65299
telemt_me_writer_teardown_success_total{mode="normal"} 73343
telemt_me_writer_teardown_noop_total 70763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 141415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 143198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 143737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 144056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 144106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 144106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144106
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.520811
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144106
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 672
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 2122
telemt_me_writer_restored_fallback_total 137
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 9010824
telemt_user_connections_current{user="hello"} 750
telemt_user_octets_from_client{user="hello"} 157699406960 (146.87 GB)
telemt_user_octets_to_client{user="hello"} 3513962197262 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 69
```