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

# Server Metrics 2026-03-22 20:15:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 83320.4 (23h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3095266
telemt_connections_bad_total 212823
telemt_connections_current 1175
telemt_connections_me_current 1175
telemt_handshake_timeouts_total 98867
telemt_upstream_connect_attempt_total 30544
telemt_upstream_connect_success_total 30543
telemt_upstream_connect_attempts_per_request{bucket="1"} 30543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 82
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1216
telemt_me_reconnect_success_total 513
telemt_me_reader_eof_total 520
telemt_me_idle_close_by_peer_total 520
telemt_me_route_drop_no_conn_total 2785263
telemt_me_route_drop_channel_closed_total 1106
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2618603
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 563
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 645
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
telemt_desync_total 11220
telemt_desync_full_logged_total 3551
telemt_desync_suppressed_total 7669
telemt_desync_frames_bucket_total{bucket="1_2"} 3005
telemt_desync_frames_bucket_total{bucket="3_10"} 4154
telemt_desync_frames_bucket_total{bucket="gt_10"} 4061
telemt_pool_swap_total 92
telemt_pool_force_close_total 2877
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 591
telemt_me_draining_writers_reap_progress_total 27957
telemt_me_writer_removed_unexpected_total 504
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2032
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26133
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25080
telemt_me_writer_teardown_success_total{mode="normal"} 28165
telemt_me_writer_teardown_noop_total 27968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56133
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 320.956920
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56133
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 591
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 454
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 2610244
telemt_user_connections_current{user="hello"} 1175
telemt_user_octets_from_client{user="hello"} 38355585708 (35.72 GB)
telemt_user_octets_to_client{user="hello"} 687654883036 (640.43 GB)
telemt_user_unique_ips_current{user="hello"} 467
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 96687.4 (26h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3846414
telemt_connections_bad_total 340580
telemt_connections_current 478
telemt_connections_me_current 478
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 97876
telemt_upstream_connect_attempt_total 58610
telemt_upstream_connect_success_total 57892
telemt_upstream_connect_fail_total 634
telemt_upstream_connect_attempts_per_request{bucket="1"} 58526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 634
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6815
telemt_me_reconnect_success_total 2656
telemt_me_reader_eof_total 2607
telemt_me_idle_close_by_peer_total 2607
telemt_me_route_drop_no_conn_total 3609694
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3064064
telemt_me_endpoint_quarantine_total 739
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 744
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_me_writers_active_current 44
telemt_desync_total 12286
telemt_desync_full_logged_total 6868
telemt_desync_suppressed_total 5418
telemt_desync_frames_bucket_total{bucket="1_2"} 2807
telemt_desync_frames_bucket_total{bucket="3_10"} 4812
telemt_desync_frames_bucket_total{bucket="gt_10"} 4667
telemt_pool_swap_total 90
telemt_pool_force_close_total 2746
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 232
telemt_me_draining_writers_reap_progress_total 38548
telemt_me_writer_removed_unexpected_total 2551
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4749
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36369
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2321
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 425
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35802
telemt_me_writer_teardown_success_total{mode="normal"} 41118
telemt_me_writer_teardown_noop_total 38549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79667
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.254345
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79667
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 232
telemt_me_refill_failed_total 166
telemt_me_writer_restored_same_endpoint_total 2343
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 3074819
telemt_user_connections_current{user="hello"} 478
telemt_user_octets_from_client{user="hello"} 40245867463 (37.48 GB)
telemt_user_octets_to_client{user="hello"} 736653660202 (686.06 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 171547.3 (47h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15976069
telemt_connections_bad_total 1548744
telemt_connections_current 1672
telemt_connections_me_current 1672
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 393045
telemt_upstream_connect_attempt_total 76187
telemt_upstream_connect_success_total 76089
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 76106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1689
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2809
telemt_me_reconnect_success_total 1446
telemt_me_reader_eof_total 1389
telemt_me_idle_close_by_peer_total 1387
telemt_me_route_drop_no_conn_total 13982206
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12729771
telemt_me_endpoint_quarantine_total 1085
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1277
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
telemt_me_writers_active_current 43
telemt_desync_total 52559
telemt_desync_full_logged_total 16547
telemt_desync_suppressed_total 36012
telemt_desync_frames_bucket_total{bucket="1_2"} 11716
telemt_desync_frames_bucket_total{bucket="3_10"} 20471
telemt_desync_frames_bucket_total{bucket="gt_10"} 20372
telemt_pool_swap_total 185
telemt_pool_force_close_total 6251
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1018
telemt_me_draining_writers_reap_progress_total 56347
telemt_me_writer_removed_unexpected_total 1341
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4935
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52030
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5781
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50096
telemt_me_writer_teardown_success_total{mode="normal"} 56965
telemt_me_writer_teardown_noop_total 56398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113363
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 313.724161
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113363
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1018
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1248
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 12730232
telemt_user_connections_current{user="hello"} 1672
telemt_user_octets_from_client{user="hello"} 186181015945 (173.39 GB)
telemt_user_octets_to_client{user="hello"} 3391545912415 (3.08 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 702
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 171548.1 (47h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11557035
telemt_connections_bad_total 1157400
telemt_connections_current 1252
telemt_connections_me_current 1252
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343013
telemt_upstream_connect_attempt_total 88724
telemt_upstream_connect_success_total 87461
telemt_upstream_connect_fail_total 850
telemt_upstream_connect_attempts_per_request{bucket="1"} 88311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36366
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3719
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 850
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4157
telemt_me_reconnect_success_total 1737
telemt_me_reader_eof_total 1603
telemt_me_idle_close_by_peer_total 1603
telemt_me_route_drop_no_conn_total 4501864
telemt_me_route_drop_channel_closed_total 495
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8610601
telemt_me_endpoint_quarantine_total 1084
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1299
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_me_writers_active_current 44
telemt_desync_total 38186
telemt_desync_full_logged_total 12850
telemt_desync_suppressed_total 25336
telemt_desync_frames_bucket_total{bucket="1_2"} 9419
telemt_desync_frames_bucket_total{bucket="3_10"} 14693
telemt_desync_frames_bucket_total{bucket="gt_10"} 14074
telemt_pool_swap_total 182
telemt_pool_force_close_total 5636
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 702
telemt_me_draining_writers_reap_progress_total 54770
telemt_me_writer_removed_unexpected_total 1641
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5060
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51198
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5130
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 506
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49134
telemt_me_writer_teardown_success_total{mode="normal"} 56258
telemt_me_writer_teardown_noop_total 54795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111053
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.712023
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111053
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 702
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1483
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 8548715
telemt_user_connections_current{user="hello"} 1252
telemt_user_octets_from_client{user="hello"} 214892029413 (200.13 GB)
telemt_user_octets_to_client{user="hello"} 3863641079046 (3.51 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 469
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 171516.0 (47h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10838938
telemt_connections_bad_total 938328
telemt_connections_current 1213
telemt_connections_me_current 1213
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 343998
telemt_upstream_connect_attempt_total 73850
telemt_upstream_connect_success_total 72700
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 72886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_timeout_total 1386
telemt_me_reconnect_attempts_total 5019
telemt_me_reconnect_success_total 2028
telemt_me_reader_eof_total 1771
telemt_me_idle_close_by_peer_total 1770
telemt_me_route_drop_no_conn_total 5267610
telemt_me_route_drop_channel_closed_total 375
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8198045
telemt_me_endpoint_quarantine_total 1163
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1258
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 62
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
telemt_desync_total 37553
telemt_desync_full_logged_total 12430
telemt_desync_suppressed_total 25123
telemt_desync_frames_bucket_total{bucket="1_2"} 9496
telemt_desync_frames_bucket_total{bucket="3_10"} 14353
telemt_desync_frames_bucket_total{bucket="gt_10"} 13704
telemt_pool_swap_total 180
telemt_pool_force_close_total 5581
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 714
telemt_me_draining_writers_reap_progress_total 54861
telemt_me_writer_removed_unexpected_total 1915
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5518
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51177
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5030
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49280
telemt_me_writer_teardown_success_total{mode="normal"} 56695
telemt_me_writer_teardown_noop_total 54932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111627
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.000172
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111627
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 714
telemt_me_refill_failed_total 159
telemt_me_writer_restored_same_endpoint_total 1746
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 8190292
telemt_user_connections_current{user="hello"} 1213
telemt_user_octets_from_client{user="hello"} 191077941145 (177.96 GB)
telemt_user_octets_to_client{user="hello"} 3409881782837 (3.10 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 459
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 41792.1 (11h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10847410
telemt_connections_bad_total 658910
telemt_connections_current 1810
telemt_connections_me_current 1810
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 235180
telemt_upstream_connect_attempt_total 45566
telemt_upstream_connect_success_total 43292
telemt_upstream_connect_fail_total 1559
telemt_upstream_connect_attempts_per_request{bucket="1"} 44851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5963
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1559
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6578
telemt_me_reconnect_success_total 927
telemt_me_reader_eof_total 580
telemt_me_idle_close_by_peer_total 580
telemt_me_route_drop_no_conn_total 25207062
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9010117
telemt_me_endpoint_quarantine_total 275
telemt_me_single_endpoint_outage_enter_total 66
telemt_me_single_endpoint_outage_exit_total 66
telemt_me_single_endpoint_outage_reconnect_attempt_total 118
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 118
telemt_me_single_endpoint_shadow_rotate_total 328
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 14688
telemt_desync_full_logged_total 3878
telemt_desync_suppressed_total 10810
telemt_desync_frames_bucket_total{bucket="1_2"} 2721
telemt_desync_frames_bucket_total{bucket="3_10"} 5975
telemt_desync_frames_bucket_total{bucket="gt_10"} 5992
telemt_pool_swap_total 42
telemt_pool_force_close_total 1536
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 436
telemt_me_draining_writers_reap_progress_total 11961
telemt_me_writer_removed_unexpected_total 823
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1784
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10950
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1234
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10425
telemt_me_writer_teardown_success_total{mode="normal"} 12734
telemt_me_writer_teardown_noop_total 11980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24714
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 50.954356
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24714
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 436
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 622
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 9032199
telemt_user_connections_current{user="hello"} 1810
telemt_user_octets_from_client{user="hello"} 82594181027 (76.92 GB)
telemt_user_octets_to_client{user="hello"} 501283803963 (466.86 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 689
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 171518.9 (47h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10726814
telemt_connections_bad_total 907651
telemt_connections_current 1621
telemt_connections_me_current 1621
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 236057
telemt_upstream_connect_attempt_total 103298
telemt_upstream_connect_success_total 102210
telemt_upstream_connect_fail_total 929
telemt_upstream_connect_attempts_per_request{bucket="1"} 103139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38495
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1340
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 929
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72391
telemt_me_reconnect_success_total 2831
telemt_me_reader_eof_total 2521
telemt_me_idle_close_by_peer_total 2519
telemt_me_route_drop_no_conn_total 5202785
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8471602
telemt_me_endpoint_quarantine_total 1133
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1283
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 45087
telemt_desync_full_logged_total 15365
telemt_desync_suppressed_total 29722
telemt_desync_frames_bucket_total{bucket="1_2"} 9139
telemt_desync_frames_bucket_total{bucket="3_10"} 17272
telemt_desync_frames_bucket_total{bucket="gt_10"} 18676
telemt_pool_swap_total 175
telemt_pool_force_close_total 5229
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 641
telemt_me_draining_writers_reap_progress_total 58804
telemt_me_writer_removed_unexpected_total 2559
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6247
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55142
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4502
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 727
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53575
telemt_me_writer_teardown_success_total{mode="normal"} 61389
telemt_me_writer_teardown_noop_total 58805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120194
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.052773
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120194
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 641
telemt_me_refill_failed_total 4285
telemt_me_writer_restored_same_endpoint_total 2380
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 8474852
telemt_user_connections_current{user="hello"} 1621
telemt_user_octets_from_client{user="hello"} 191902469485 (178.72 GB)
telemt_user_octets_to_client{user="hello"} 3222570701180 (2.93 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 630
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 108355.1 (30h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11317474
telemt_connections_bad_total 453396
telemt_connections_current 1194
telemt_connections_me_current 1194
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4654399
telemt_upstream_connect_attempt_total 51374
telemt_upstream_connect_success_total 50991
telemt_upstream_connect_fail_total 374
telemt_upstream_connect_attempts_per_request{bucket="1"} 51365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22844
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 374
telemt_me_reconnect_attempts_total 48547
telemt_me_reconnect_success_total 1676
telemt_me_reader_eof_total 1334
telemt_me_idle_close_by_peer_total 1333
telemt_me_route_drop_no_conn_total 4040833
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5451709
telemt_me_endpoint_quarantine_total 702
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 819
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30642
telemt_desync_full_logged_total 10379
telemt_desync_suppressed_total 20263
telemt_desync_frames_bucket_total{bucket="1_2"} 6109
telemt_desync_frames_bucket_total{bucket="3_10"} 12127
telemt_desync_frames_bucket_total{bucket="gt_10"} 12406
telemt_pool_swap_total 114
telemt_pool_force_close_total 3485
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 37757
telemt_me_writer_removed_unexpected_total 1394
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3338
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35847
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3044
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34272
telemt_me_writer_teardown_success_total{mode="normal"} 39185
telemt_me_writer_teardown_noop_total 37764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76949
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.479464
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76949
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 2724
telemt_me_writer_restored_same_endpoint_total 1490
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5444531
telemt_user_connections_current{user="hello"} 1194
telemt_user_octets_from_client{user="hello"} 117270328096 (109.22 GB)
telemt_user_octets_to_client{user="hello"} 2085772757890 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 89325.4 (24h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1346773
telemt_connections_bad_total 30240
telemt_connections_current 949
telemt_connections_me_current 949
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 25185
telemt_upstream_connect_attempt_total 42278
telemt_upstream_connect_success_total 42148
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 42251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 723
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1995
telemt_me_reconnect_success_total 815
telemt_me_reader_eof_total 795
telemt_me_idle_close_by_peer_total 795
telemt_me_route_drop_no_conn_total 471517
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1196015
telemt_me_endpoint_quarantine_total 741
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 737
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
telemt_me_writers_active_current 42
telemt_desync_total 7197
telemt_desync_full_logged_total 2229
telemt_desync_suppressed_total 4968
telemt_desync_frames_bucket_total{bucket="1_2"} 1581
telemt_desync_frames_bucket_total{bucket="3_10"} 2829
telemt_desync_frames_bucket_total{bucket="gt_10"} 2787
telemt_pool_swap_total 96
telemt_pool_force_close_total 2492
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 144
telemt_me_draining_writers_reap_progress_total 35223
telemt_me_writer_removed_unexpected_total 767
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2787
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33234
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2405
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32731
telemt_me_writer_teardown_success_total{mode="normal"} 36021
telemt_me_writer_teardown_noop_total 35227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71248
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.529566
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71248
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 144
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 691
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 1192081
telemt_user_connections_current{user="hello"} 949
telemt_user_octets_from_client{user="hello"} 22949288117 (21.37 GB)
telemt_user_octets_to_client{user="hello"} 503892647803 (469.29 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 326
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 171523.8 (47h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13041386
telemt_connections_bad_total 1524226
telemt_connections_current 1472
telemt_connections_me_current 1472
telemt_handshake_timeouts_total 373776
telemt_upstream_connect_attempt_total 64799
telemt_upstream_connect_success_total 64467
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 64664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32475
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2536
telemt_me_reconnect_success_total 1329
telemt_me_reader_eof_total 1295
telemt_me_idle_close_by_peer_total 1295
telemt_me_route_drop_no_conn_total 4423113
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9869068
telemt_me_endpoint_quarantine_total 1151
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1284
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 40903
telemt_desync_full_logged_total 13336
telemt_desync_suppressed_total 27567
telemt_desync_frames_bucket_total{bucket="1_2"} 9773
telemt_desync_frames_bucket_total{bucket="3_10"} 15083
telemt_desync_frames_bucket_total{bucket="gt_10"} 16047
telemt_pool_swap_total 190
telemt_pool_force_close_total 5225
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 652
telemt_me_draining_writers_reap_progress_total 58390
telemt_me_writer_removed_unexpected_total 1246
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4769
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54906
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5051
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53165
telemt_me_writer_teardown_success_total{mode="normal"} 59675
telemt_me_writer_teardown_noop_total 58392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118067
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.463484
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118067
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 652
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1162
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 9836728
telemt_user_connections_current{user="hello"} 1472
telemt_user_octets_from_client{user="hello"} 192167215260 (178.97 GB)
telemt_user_octets_to_client{user="hello"} 4346159272360 (3.95 TB)
telemt_user_unique_ips_current{user="hello"} 527
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 171520.5 (47h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11341322
telemt_connections_bad_total 1283533
telemt_connections_current 1286
telemt_connections_me_current 1286
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 298536
telemt_upstream_connect_attempt_total 91268
telemt_upstream_connect_success_total 90444
telemt_upstream_connect_fail_total 617
telemt_upstream_connect_attempts_per_request{bucket="1"} 91061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 617
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9810
telemt_me_reconnect_success_total 2352
telemt_me_reader_eof_total 2199
telemt_me_idle_close_by_peer_total 2198
telemt_me_seq_mismatch_total 79
telemt_me_route_drop_no_conn_total 5597607
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8769704
telemt_me_endpoint_quarantine_total 1308
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1284
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 40052
telemt_desync_full_logged_total 12943
telemt_desync_suppressed_total 27109
telemt_desync_frames_bucket_total{bucket="1_2"} 9986
telemt_desync_frames_bucket_total{bucket="3_10"} 14886
telemt_desync_frames_bucket_total{bucket="gt_10"} 15180
telemt_pool_swap_total 180
telemt_pool_force_close_total 5023
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 636
telemt_me_draining_writers_reap_progress_total 58188
telemt_me_writer_removed_unexpected_total 2231
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6108
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54387
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4552
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53165
telemt_me_writer_teardown_success_total{mode="normal"} 60495
telemt_me_writer_teardown_noop_total 58193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118688
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.178689
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118688
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 636
telemt_me_refill_failed_total 385
telemt_me_writer_restored_same_endpoint_total 1918
telemt_me_writer_restored_fallback_total 109
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 8775252
telemt_user_connections_current{user="hello"} 1286
telemt_user_octets_from_client{user="hello"} 155394976437 (144.72 GB)
telemt_user_octets_to_client{user="hello"} 3396287623351 (3.09 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 483
telemt_user_unique_ips_recent_window{user="hello"} 173
```