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

# Server Metrics 2026-03-22 20:04:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 82710.9 (22h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3074034
telemt_connections_bad_total 210264
telemt_connections_current 1150
telemt_connections_me_current 1150
telemt_handshake_timeouts_total 98426
telemt_upstream_connect_attempt_total 30317
telemt_upstream_connect_success_total 30316
telemt_upstream_connect_attempts_per_request{bucket="1"} 30316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19733
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 77
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1197
telemt_me_reconnect_success_total 510
telemt_me_reader_eof_total 516
telemt_me_idle_close_by_peer_total 516
telemt_me_route_drop_no_conn_total 2766348
telemt_me_route_drop_channel_closed_total 1094
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2601452
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 559
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 640
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
telemt_desync_total 11142
telemt_desync_full_logged_total 3532
telemt_desync_suppressed_total 7610
telemt_desync_frames_bucket_total{bucket="1_2"} 2981
telemt_desync_frames_bucket_total{bucket="3_10"} 4133
telemt_desync_frames_bucket_total{bucket="gt_10"} 4028
telemt_pool_swap_total 91
telemt_pool_force_close_total 2818
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 587
telemt_me_draining_writers_reap_progress_total 27715
telemt_me_writer_removed_unexpected_total 500
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2019
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25927
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2765
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24897
telemt_me_writer_teardown_success_total{mode="normal"} 27946
telemt_me_writer_teardown_noop_total 27725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55671
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 311.071920
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55671
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 587
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 452
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 2593170
telemt_user_connections_current{user="hello"} 1150
telemt_user_octets_from_client{user="hello"} 38191917188 (35.57 GB)
telemt_user_octets_to_client{user="hello"} 681376764920 (634.58 GB)
telemt_user_unique_ips_current{user="hello"} 480
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 96076.9 (26h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3838799
telemt_connections_bad_total 340392
telemt_connections_current 792
telemt_connections_me_current 792
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 97721
telemt_upstream_connect_attempt_total 58313
telemt_upstream_connect_success_total 57598
telemt_upstream_connect_fail_total 631
telemt_upstream_connect_attempts_per_request{bucket="1"} 58229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 631
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6811
telemt_me_reconnect_success_total 2652
telemt_me_reader_eof_total 2602
telemt_me_idle_close_by_peer_total 2602
telemt_me_route_drop_no_conn_total 3607221
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3057172
telemt_me_endpoint_quarantine_total 734
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 738
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
telemt_me_writers_active_current 46
telemt_desync_total 12251
telemt_desync_full_logged_total 6847
telemt_desync_suppressed_total 5404
telemt_desync_frames_bucket_total{bucket="1_2"} 2803
telemt_desync_frames_bucket_total{bucket="3_10"} 4804
telemt_desync_frames_bucket_total{bucket="gt_10"} 4644
telemt_pool_swap_total 89
telemt_pool_force_close_total 2722
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 230
telemt_me_draining_writers_reap_progress_total 38264
telemt_me_writer_removed_unexpected_total 2547
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4727
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36102
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2297
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 425
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35542
telemt_me_writer_teardown_success_total{mode="normal"} 40829
telemt_me_writer_teardown_noop_total 38265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79094
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.143273
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79094
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 230
telemt_me_refill_failed_total 166
telemt_me_writer_restored_same_endpoint_total 2339
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 3067938
telemt_user_connections_current{user="hello"} 792
telemt_user_octets_from_client{user="hello"} 40096013703 (37.34 GB)
telemt_user_octets_to_client{user="hello"} 732888984762 (682.56 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 473
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 170936.9 (47h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15956927
telemt_connections_bad_total 1546824
telemt_connections_current 2071
telemt_connections_me_current 2071
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 392707
telemt_upstream_connect_attempt_total 75949
telemt_upstream_connect_success_total 75852
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 75869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1687
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2809
telemt_me_reconnect_success_total 1446
telemt_me_reader_eof_total 1389
telemt_me_idle_close_by_peer_total 1387
telemt_me_route_drop_no_conn_total 13976642
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12713804
telemt_me_endpoint_quarantine_total 1076
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1272
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
telemt_me_writers_active_current 45
telemt_desync_total 52438
telemt_desync_full_logged_total 16515
telemt_desync_suppressed_total 35923
telemt_desync_frames_bucket_total{bucket="1_2"} 11694
telemt_desync_frames_bucket_total{bucket="3_10"} 20432
telemt_desync_frames_bucket_total{bucket="gt_10"} 20312
telemt_pool_swap_total 184
telemt_pool_force_close_total 6219
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1013
telemt_me_draining_writers_reap_progress_total 56116
telemt_me_writer_removed_unexpected_total 1341
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4921
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51813
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5751
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 468
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49897
telemt_me_writer_teardown_success_total{mode="normal"} 56734
telemt_me_writer_teardown_noop_total 56167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112901
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 313.693083
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112901
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1013
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1248
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 12714294
telemt_user_connections_current{user="hello"} 2071
telemt_user_octets_from_client{user="hello"} 185981275237 (173.21 GB)
telemt_user_octets_to_client{user="hello"} 3382890629479 (3.08 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 852
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 170938.4 (47h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11540967
telemt_connections_bad_total 1154651
telemt_connections_current 1357
telemt_connections_me_current 1357
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 342901
telemt_upstream_connect_attempt_total 88433
telemt_upstream_connect_success_total 87200
telemt_upstream_connect_fail_total 845
telemt_upstream_connect_attempts_per_request{bucket="1"} 88045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36234
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3708
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 845
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4144
telemt_me_reconnect_success_total 1724
telemt_me_reader_eof_total 1593
telemt_me_idle_close_by_peer_total 1593
telemt_me_route_drop_no_conn_total 4495819
telemt_me_route_drop_channel_closed_total 494
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8597805
telemt_me_endpoint_quarantine_total 1076
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1293
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
telemt_me_writers_active_current 45
telemt_desync_total 38137
telemt_desync_full_logged_total 12831
telemt_desync_suppressed_total 25306
telemt_desync_frames_bucket_total{bucket="1_2"} 9400
telemt_desync_frames_bucket_total{bucket="3_10"} 14679
telemt_desync_frames_bucket_total{bucket="gt_10"} 14058
telemt_pool_swap_total 181
telemt_pool_force_close_total 5608
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 702
telemt_me_draining_writers_reap_progress_total 54548
telemt_me_writer_removed_unexpected_total 1630
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5027
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50998
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5105
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 503
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48940
telemt_me_writer_teardown_success_total{mode="normal"} 56025
telemt_me_writer_teardown_noop_total 54573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110598
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.661596
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110598
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 702
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1474
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 8535939
telemt_user_connections_current{user="hello"} 1357
telemt_user_octets_from_client{user="hello"} 214622625913 (199.88 GB)
telemt_user_octets_to_client{user="hello"} 3858814220530 (3.51 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 545
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 170902.2 (47h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10823166
telemt_connections_bad_total 936598
telemt_connections_current 1141
telemt_connections_me_current 1141
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 343886
telemt_upstream_connect_attempt_total 73559
telemt_upstream_connect_success_total 72429
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 72614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34676
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1615
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 5009
telemt_me_reconnect_success_total 2019
telemt_me_reader_eof_total 1765
telemt_me_idle_close_by_peer_total 1764
telemt_me_route_drop_no_conn_total 5263050
telemt_me_route_drop_channel_closed_total 375
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8184980
telemt_me_endpoint_quarantine_total 1158
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1252
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 61
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
telemt_desync_total 37531
telemt_desync_full_logged_total 12423
telemt_desync_suppressed_total 25108
telemt_desync_frames_bucket_total{bucket="1_2"} 9494
telemt_desync_frames_bucket_total{bucket="3_10"} 14348
telemt_desync_frames_bucket_total{bucket="gt_10"} 13689
telemt_pool_swap_total 179
telemt_pool_force_close_total 5553
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 713
telemt_me_draining_writers_reap_progress_total 54636
telemt_me_writer_removed_unexpected_total 1907
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5490
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50972
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5002
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49083
telemt_me_writer_teardown_success_total{mode="normal"} 56462
telemt_me_writer_teardown_noop_total 54707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111169
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.979471
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111169
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 713
telemt_me_refill_failed_total 159
telemt_me_writer_restored_same_endpoint_total 1738
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 8177246
telemt_user_connections_current{user="hello"} 1141
telemt_user_octets_from_client{user="hello"} 190723197741 (177.62 GB)
telemt_user_octets_to_client{user="hello"} 3403012973745 (3.10 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 453
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 41182.3 (11h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10823926
telemt_connections_bad_total 658212
telemt_connections_current 1821
telemt_connections_me_current 1821
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 233804
telemt_upstream_connect_attempt_total 45293
telemt_upstream_connect_success_total 43029
telemt_upstream_connect_fail_total 1553
telemt_upstream_connect_attempts_per_request{bucket="1"} 44582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13647
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5961
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1553
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6540
telemt_me_reconnect_success_total 911
telemt_me_reader_eof_total 569
telemt_me_idle_close_by_peer_total 569
telemt_me_route_drop_no_conn_total 25199795
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8990028
telemt_me_endpoint_quarantine_total 261
telemt_me_single_endpoint_outage_enter_total 65
telemt_me_single_endpoint_outage_exit_total 65
telemt_me_single_endpoint_outage_reconnect_attempt_total 117
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 117
telemt_me_single_endpoint_shadow_rotate_total 320
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
telemt_me_writers_active_current 45
telemt_desync_total 14626
telemt_desync_full_logged_total 3858
telemt_desync_suppressed_total 10768
telemt_desync_frames_bucket_total{bucket="1_2"} 2700
telemt_desync_frames_bucket_total{bucket="3_10"} 5953
telemt_desync_frames_bucket_total{bucket="gt_10"} 5973
telemt_pool_swap_total 41
telemt_pool_force_close_total 1507
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 434
telemt_me_draining_writers_reap_progress_total 11734
telemt_me_writer_removed_unexpected_total 813
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1754
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10742
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1206
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 301
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10227
telemt_me_writer_teardown_success_total{mode="normal"} 12496
telemt_me_writer_teardown_noop_total 11753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24249
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 50.377150
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24249
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 434
telemt_me_refill_failed_total 311
telemt_me_writer_restored_same_endpoint_total 613
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 9012124
telemt_user_connections_current{user="hello"} 1821
telemt_user_octets_from_client{user="hello"} 82324026983 (76.67 GB)
telemt_user_octets_to_client{user="hello"} 493254554863 (459.38 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 704
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 170908.9 (47h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10708844
telemt_connections_bad_total 905402
telemt_connections_current 1526
telemt_connections_me_current 1526
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 235583
telemt_upstream_connect_attempt_total 102998
telemt_upstream_connect_success_total 101913
telemt_upstream_connect_fail_total 926
telemt_upstream_connect_attempts_per_request{bucket="1"} 102839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38350
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1339
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 926
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72385
telemt_me_reconnect_success_total 2826
telemt_me_reader_eof_total 2516
telemt_me_idle_close_by_peer_total 2514
telemt_me_route_drop_no_conn_total 5198041
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8457305
telemt_me_endpoint_quarantine_total 1126
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1275
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
telemt_me_writers_active_current 49
telemt_desync_total 45031
telemt_desync_full_logged_total 15332
telemt_desync_suppressed_total 29699
telemt_desync_frames_bucket_total{bucket="1_2"} 9132
telemt_desync_frames_bucket_total{bucket="3_10"} 17251
telemt_desync_frames_bucket_total{bucket="gt_10"} 18648
telemt_pool_swap_total 174
telemt_pool_force_close_total 5198
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 639
telemt_me_draining_writers_reap_progress_total 58533
telemt_me_writer_removed_unexpected_total 2554
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6233
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54880
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4471
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 727
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53335
telemt_me_writer_teardown_success_total{mode="normal"} 61113
telemt_me_writer_teardown_noop_total 58534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119647
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.025307
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119647
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 639
telemt_me_refill_failed_total 4285
telemt_me_writer_restored_same_endpoint_total 2375
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 8460574
telemt_user_connections_current{user="hello"} 1526
telemt_user_octets_from_client{user="hello"} 191710065777 (178.54 GB)
telemt_user_octets_to_client{user="hello"} 3215906789404 (2.92 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 634
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 107745.1 (29h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11295632
telemt_connections_bad_total 450828
telemt_connections_current 1285
telemt_connections_me_current 1285
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4650489
telemt_upstream_connect_attempt_total 51103
telemt_upstream_connect_success_total 50721
telemt_upstream_connect_fail_total 372
telemt_upstream_connect_attempts_per_request{bucket="1"} 51093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 372
telemt_me_reconnect_attempts_total 48490
telemt_me_reconnect_success_total 1672
telemt_me_reader_eof_total 1329
telemt_me_idle_close_by_peer_total 1328
telemt_me_route_drop_no_conn_total 4037118
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5438830
telemt_me_endpoint_quarantine_total 696
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 812
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
telemt_me_writers_active_current 42
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30536
telemt_desync_full_logged_total 10352
telemt_desync_suppressed_total 20184
telemt_desync_frames_bucket_total{bucket="1_2"} 6089
telemt_desync_frames_bucket_total{bucket="3_10"} 12078
telemt_desync_frames_bucket_total{bucket="gt_10"} 12369
telemt_pool_swap_total 113
telemt_pool_force_close_total 3456
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 351
telemt_me_draining_writers_reap_progress_total 37518
telemt_me_writer_removed_unexpected_total 1389
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3321
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35620
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3016
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34062
telemt_me_writer_teardown_success_total{mode="normal"} 38941
telemt_me_writer_teardown_noop_total 37525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76466
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.475147
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76466
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 351
telemt_me_refill_failed_total 2721
telemt_me_writer_restored_same_endpoint_total 1488
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5431687
telemt_user_connections_current{user="hello"} 1285
telemt_user_octets_from_client{user="hello"} 117133667064 (109.09 GB)
telemt_user_octets_to_client{user="hello"} 2080141554010 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 515
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 88716.0 (24h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1334710
telemt_connections_bad_total 29261
telemt_connections_current 972
telemt_connections_me_current 972
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 25079
telemt_upstream_connect_attempt_total 42055
telemt_upstream_connect_success_total 41929
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 42028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22312
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 717
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1939
telemt_me_reconnect_success_total 809
telemt_me_reader_eof_total 787
telemt_me_idle_close_by_peer_total 787
telemt_me_route_drop_no_conn_total 466956
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1185407
telemt_me_endpoint_quarantine_total 736
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 731
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 7071
telemt_desync_full_logged_total 2194
telemt_desync_suppressed_total 4877
telemt_desync_frames_bucket_total{bucket="1_2"} 1569
telemt_desync_frames_bucket_total{bucket="3_10"} 2788
telemt_desync_frames_bucket_total{bucket="gt_10"} 2714
telemt_pool_swap_total 95
telemt_pool_force_close_total 2460
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 142
telemt_me_draining_writers_reap_progress_total 35020
telemt_me_writer_removed_unexpected_total 759
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2762
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33048
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2375
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32560
telemt_me_writer_teardown_success_total{mode="normal"} 35810
telemt_me_writer_teardown_noop_total 35024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70834
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.376592
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70834
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 142
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 686
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 1181493
telemt_user_connections_current{user="hello"} 972
telemt_user_octets_from_client{user="hello"} 22816666521 (21.25 GB)
telemt_user_octets_to_client{user="hello"} 500254329971 (465.90 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 170913.4 (47h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13021159
telemt_connections_bad_total 1518275
telemt_connections_current 1458
telemt_connections_me_current 1458
telemt_handshake_timeouts_total 373353
telemt_upstream_connect_attempt_total 64505
telemt_upstream_connect_success_total 64173
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 64370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32326
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2527
telemt_me_reconnect_success_total 1320
telemt_me_reader_eof_total 1285
telemt_me_idle_close_by_peer_total 1285
telemt_me_route_drop_no_conn_total 4419356
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9856081
telemt_me_endpoint_quarantine_total 1142
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1278
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_active_current 47
telemt_desync_total 40819
telemt_desync_full_logged_total 13309
telemt_desync_suppressed_total 27510
telemt_desync_frames_bucket_total{bucket="1_2"} 9738
telemt_desync_frames_bucket_total{bucket="3_10"} 15062
telemt_desync_frames_bucket_total{bucket="gt_10"} 16019
telemt_pool_swap_total 189
telemt_pool_force_close_total 5201
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 652
telemt_me_draining_writers_reap_progress_total 58124
telemt_me_writer_removed_unexpected_total 1236
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4739
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54660
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5027
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52923
telemt_me_writer_teardown_success_total{mode="normal"} 59399
telemt_me_writer_teardown_noop_total 58126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117525
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.444184
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117525
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 652
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1153
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 9823766
telemt_user_connections_current{user="hello"} 1458
telemt_user_octets_from_client{user="hello"} 192059112256 (178.87 GB)
telemt_user_octets_to_client{user="hello"} 4340269279792 (3.95 TB)
telemt_user_unique_ips_current{user="hello"} 552
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 170910.2 (47h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11324963
telemt_connections_bad_total 1282549
telemt_connections_current 1445
telemt_connections_me_current 1445
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 297957
telemt_upstream_connect_attempt_total 90971
telemt_upstream_connect_success_total 90151
telemt_upstream_connect_fail_total 614
telemt_upstream_connect_attempts_per_request{bucket="1"} 90765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37885
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 614
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9762
telemt_me_reconnect_success_total 2343
telemt_me_reader_eof_total 2189
telemt_me_idle_close_by_peer_total 2188
telemt_me_seq_mismatch_total 78
telemt_me_route_drop_no_conn_total 5593991
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8755411
telemt_me_endpoint_quarantine_total 1304
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1276
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 39977
telemt_desync_full_logged_total 12917
telemt_desync_suppressed_total 27060
telemt_desync_frames_bucket_total{bucket="1_2"} 9978
telemt_desync_frames_bucket_total{bucket="3_10"} 14861
telemt_desync_frames_bucket_total{bucket="gt_10"} 15138
telemt_pool_swap_total 179
telemt_pool_force_close_total 4997
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 635
telemt_me_draining_writers_reap_progress_total 57927
telemt_me_writer_removed_unexpected_total 2222
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6078
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54145
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4526
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52930
telemt_me_writer_teardown_success_total{mode="normal"} 60223
telemt_me_writer_teardown_noop_total 57932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118155
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.171574
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118155
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 635
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 1912
telemt_me_writer_restored_fallback_total 108
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 8760973
telemt_user_connections_current{user="hello"} 1445
telemt_user_octets_from_client{user="hello"} 155186440177 (144.53 GB)
telemt_user_octets_to_client{user="hello"} 3389061461199 (3.08 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 550
telemt_user_unique_ips_recent_window{user="hello"} 178
```