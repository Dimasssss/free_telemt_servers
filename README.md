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

# Server Metrics 2026-03-23 02:17:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 105042.4 (29h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3609104
telemt_connections_bad_total 335054
telemt_connections_current 936
telemt_connections_me_current 936
telemt_handshake_timeouts_total 114140
telemt_upstream_connect_attempt_total 39152
telemt_upstream_connect_success_total 39151
telemt_upstream_connect_attempts_per_request{bucket="1"} 39151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1412
telemt_me_reconnect_success_total 615
telemt_me_reader_eof_total 632
telemt_me_idle_close_by_peer_total 632
telemt_me_route_drop_no_conn_total 2996642
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2963220
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 743
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 821
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
telemt_me_writers_active_current 43
telemt_desync_total 12786
telemt_desync_full_logged_total 4035
telemt_desync_suppressed_total 8751
telemt_desync_frames_bucket_total{bucket="1_2"} 3409
telemt_desync_frames_bucket_total{bucket="3_10"} 4663
telemt_desync_frames_bucket_total{bucket="gt_10"} 4714
telemt_pool_swap_total 116
telemt_pool_force_close_total 3560
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 666
telemt_me_draining_writers_reap_progress_total 35853
telemt_me_writer_removed_unexpected_total 609
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2551
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33560
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3504
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32293
telemt_me_writer_teardown_success_total{mode="normal"} 36111
telemt_me_writer_teardown_noop_total 35864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71975
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 378.809235
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71975
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 666
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 551
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2952200
telemt_user_connections_current{user="hello"} 936
telemt_user_octets_from_client{user="hello"} 42245580728 (39.34 GB)
telemt_user_octets_to_client{user="hello"} 807946609668 (752.46 GB)
telemt_user_unique_ips_current{user="hello"} 436
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 118408.3 (32h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4020696
telemt_connections_bad_total 372034
telemt_connections_current 240
telemt_connections_me_current 240
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 101106
telemt_upstream_connect_attempt_total 73715
telemt_upstream_connect_success_total 72813
telemt_upstream_connect_fail_total 795
telemt_upstream_connect_attempts_per_request{bucket="1"} 73608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32160
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 795
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10287
telemt_me_reconnect_success_total 3681
telemt_me_reader_eof_total 3667
telemt_me_idle_close_by_peer_total 3667
telemt_me_route_drop_no_conn_total 3643522
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3193777
telemt_me_endpoint_quarantine_total 956
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 47
telemt_me_single_endpoint_outage_exit_total 47
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 928
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 42
telemt_desync_total 13029
telemt_desync_full_logged_total 7316
telemt_desync_suppressed_total 5713
telemt_desync_frames_bucket_total{bucket="1_2"} 2958
telemt_desync_frames_bucket_total{bucket="3_10"} 5116
telemt_desync_frames_bucket_total{bucket="gt_10"} 4955
telemt_pool_swap_total 111
telemt_pool_force_close_total 3139
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 48979
telemt_me_writer_removed_unexpected_total 3596
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6374
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46235
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2681
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45840
telemt_me_writer_teardown_success_total{mode="normal"} 52609
telemt_me_writer_teardown_noop_total 48980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101589
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.649750
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101589
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 257
telemt_me_writer_restored_same_endpoint_total 3271
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 3207142
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 43246447770 (40.28 GB)
telemt_user_octets_to_client{user="hello"} 795700609726 (741.05 GB)
telemt_user_msgs_from_client{user="hello"} 49767
telemt_user_msgs_to_client{user="hello"} 185105
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 193268.3 (53h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16389058
telemt_connections_bad_total 1660133
telemt_connections_current 1022
telemt_connections_me_current 1022
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 398293
telemt_upstream_connect_attempt_total 86864
telemt_upstream_connect_success_total 86758
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 86775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42577
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1723
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3033
telemt_me_reconnect_success_total 1609
telemt_me_reader_eof_total 1556
telemt_me_idle_close_by_peer_total 1554
telemt_me_route_drop_no_conn_total 14052923
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13013296
telemt_me_endpoint_quarantine_total 1289
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1456
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
telemt_me_writers_active_current 46
telemt_desync_total 53985
telemt_desync_full_logged_total 17174
telemt_desync_suppressed_total 36811
telemt_desync_frames_bucket_total{bucket="1_2"} 12041
telemt_desync_frames_bucket_total{bucket="3_10"} 21082
telemt_desync_frames_bucket_total{bucket="gt_10"} 20862
telemt_pool_swap_total 209
telemt_pool_force_close_total 6811
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1066
telemt_me_draining_writers_reap_progress_total 66110
telemt_me_writer_removed_unexpected_total 1497
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5594
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61291
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6341
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59299
telemt_me_writer_teardown_success_total{mode="normal"} 66885
telemt_me_writer_teardown_noop_total 66163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 131387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133048
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.888313
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133048
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1066
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1392
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 13013292
telemt_user_connections_current{user="hello"} 1022
telemt_user_octets_from_client{user="hello"} 197423487881 (183.86 GB)
telemt_user_octets_to_client{user="hello"} 3503392965991 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 467
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 193269.5 (53h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11933423
telemt_connections_bad_total 1246084
telemt_connections_current 637
telemt_connections_me_current 637
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344840
telemt_upstream_connect_attempt_total 101225
telemt_upstream_connect_success_total 99895
telemt_upstream_connect_fail_total 877
telemt_upstream_connect_attempts_per_request{bucket="1"} 100772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42474
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3802
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 877
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4468
telemt_me_reconnect_success_total 1919
telemt_me_reader_eof_total 1785
telemt_me_idle_close_by_peer_total 1785
telemt_me_route_drop_no_conn_total 4561957
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8849583
telemt_me_endpoint_quarantine_total 1304
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1476
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
telemt_me_writers_active_current 46
telemt_desync_total 39030
telemt_desync_full_logged_total 13143
telemt_desync_suppressed_total 25887
telemt_desync_frames_bucket_total{bucket="1_2"} 9672
telemt_desync_frames_bucket_total{bucket="3_10"} 14990
telemt_desync_frames_bucket_total{bucket="gt_10"} 14368
telemt_pool_swap_total 206
telemt_pool_force_close_total 6164
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 713
telemt_me_draining_writers_reap_progress_total 64316
telemt_me_writer_removed_unexpected_total 1812
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5706
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60281
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5652
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58152
telemt_me_writer_teardown_success_total{mode="normal"} 65987
telemt_me_writer_teardown_noop_total 64341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130328
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.520841
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130328
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 713
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1642
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 8787320
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 218083645596 (203.11 GB)
telemt_user_octets_to_client{user="hello"} 3972645805263 (3.61 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 193233.6 (53h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11092728
telemt_connections_bad_total 983366
telemt_connections_current 517
telemt_connections_me_current 517
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345784
telemt_upstream_connect_attempt_total 85515
telemt_upstream_connect_success_total 83954
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 84159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40939
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5778
telemt_me_reconnect_success_total 2400
telemt_me_reader_eof_total 2144
telemt_me_idle_close_by_peer_total 2143
telemt_me_route_drop_no_conn_total 5342337
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8381608
telemt_me_endpoint_quarantine_total 1361
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1436
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38246
telemt_desync_full_logged_total 12673
telemt_desync_suppressed_total 25573
telemt_desync_frames_bucket_total{bucket="1_2"} 9660
telemt_desync_frames_bucket_total{bucket="3_10"} 14643
telemt_desync_frames_bucket_total{bucket="gt_10"} 13943
telemt_pool_swap_total 202
telemt_pool_force_close_total 6060
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 746
telemt_me_draining_writers_reap_progress_total 64711
telemt_me_writer_removed_unexpected_total 2293
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6445
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60492
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58651
telemt_me_writer_teardown_success_total{mode="normal"} 66937
telemt_me_writer_teardown_noop_total 64782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 131238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131719
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.844860
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131719
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 746
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2088
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8373547
telemt_user_connections_current{user="hello"} 517
telemt_user_octets_from_client{user="hello"} 192901968359 (179.65 GB)
telemt_user_octets_to_client{user="hello"} 3478591549301 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 63513.6 (17h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11313041
telemt_connections_bad_total 669772
telemt_connections_current 1002
telemt_connections_me_current 1002
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 281942
telemt_upstream_connect_attempt_total 59903
telemt_upstream_connect_success_total 56784
telemt_upstream_connect_fail_total 2041
telemt_upstream_connect_attempts_per_request{bucket="1"} 58825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6018
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2041
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7814
telemt_me_reconnect_success_total 1283
telemt_me_reader_eof_total 812
telemt_me_idle_close_by_peer_total 811
telemt_me_route_drop_no_conn_total 25299655
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9382084
telemt_me_endpoint_quarantine_total 475
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 508
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 16461
telemt_desync_full_logged_total 4509
telemt_desync_suppressed_total 11952
telemt_desync_frames_bucket_total{bucket="1_2"} 3131
telemt_desync_frames_bucket_total{bucket="3_10"} 6711
telemt_desync_frames_bucket_total{bucket="gt_10"} 6619
telemt_pool_swap_total 66
telemt_pool_force_close_total 2110
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 491
telemt_me_draining_writers_reap_progress_total 20327
telemt_me_writer_removed_unexpected_total 1168
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2677
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18762
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1803
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18217
telemt_me_writer_teardown_success_total{mode="normal"} 21439
telemt_me_writer_teardown_noop_total 20346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41785
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.965081
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41785
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 491
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 828
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 9407930
telemt_user_connections_current{user="hello"} 1002
telemt_user_octets_from_client{user="hello"} 87655446498 (81.64 GB)
telemt_user_octets_to_client{user="hello"} 623828833874 (580.99 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 193240.1 (53h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11048467
telemt_connections_bad_total 964953
telemt_connections_current 799
telemt_connections_me_current 799
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 243479
telemt_upstream_connect_attempt_total 114339
telemt_upstream_connect_success_total 113164
telemt_upstream_connect_fail_total 1001
telemt_upstream_connect_attempts_per_request{bucket="1"} 114165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44436
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1001
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73062
telemt_me_reconnect_success_total 3133
telemt_me_reader_eof_total 2825
telemt_me_idle_close_by_peer_total 2823
telemt_me_route_drop_no_conn_total 5269322
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8707547
telemt_me_endpoint_quarantine_total 1307
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1464
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
telemt_me_writers_active_current 46
telemt_desync_total 46389
telemt_desync_full_logged_total 15914
telemt_desync_suppressed_total 30475
telemt_desync_frames_bucket_total{bucket="1_2"} 9433
telemt_desync_frames_bucket_total{bucket="3_10"} 17755
telemt_desync_frames_bucket_total{bucket="gt_10"} 19201
telemt_pool_swap_total 198
telemt_pool_force_close_total 5772
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 667
telemt_me_draining_writers_reap_progress_total 68748
telemt_me_writer_removed_unexpected_total 2848
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6987
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64650
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5023
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62976
telemt_me_writer_teardown_success_total{mode="normal"} 71637
telemt_me_writer_teardown_noop_total 68749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 138234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 139650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140386
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.290521
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140386
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 667
telemt_me_refill_failed_total 4304
telemt_me_writer_restored_same_endpoint_total 2640
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 8710482
telemt_user_connections_current{user="hello"} 799
telemt_user_octets_from_client{user="hello"} 195996650485 (182.54 GB)
telemt_user_octets_to_client{user="hello"} 3329403057196 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 360
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 130076.4 (36h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11750471
telemt_connections_bad_total 482881
telemt_connections_current 545
telemt_connections_me_current 545
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4767466
telemt_upstream_connect_attempt_total 62934
telemt_upstream_connect_success_total 62474
telemt_upstream_connect_fail_total 448
telemt_upstream_connect_attempts_per_request{bucket="1"} 62922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 448
telemt_me_reconnect_attempts_total 49097
telemt_me_reconnect_success_total 1864
telemt_me_reader_eof_total 1541
telemt_me_idle_close_by_peer_total 1540
telemt_me_route_drop_no_conn_total 4098665
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5647476
telemt_me_endpoint_quarantine_total 887
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1001
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31778
telemt_desync_full_logged_total 10852
telemt_desync_suppressed_total 20926
telemt_desync_frames_bucket_total{bucket="1_2"} 6334
telemt_desync_frames_bucket_total{bucket="3_10"} 12541
telemt_desync_frames_bucket_total{bucket="gt_10"} 12903
telemt_pool_swap_total 138
telemt_pool_force_close_total 3982
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 48286
telemt_me_writer_removed_unexpected_total 1586
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3908
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46013
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3541
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44304
telemt_me_writer_teardown_success_total{mode="normal"} 49921
telemt_me_writer_teardown_noop_total 48293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98214
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.720167
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98214
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 2744
telemt_me_writer_restored_same_endpoint_total 1648
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5639602
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 120122675212 (111.87 GB)
telemt_user_octets_to_client{user="hello"} 2189656108954 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 111047.2 (30h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1549641
telemt_connections_bad_total 36841
telemt_connections_current 509
telemt_connections_me_current 509
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 31750
telemt_upstream_connect_attempt_total 52577
telemt_upstream_connect_success_total 52414
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 52549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 797
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2311
telemt_me_reconnect_success_total 942
telemt_me_reader_eof_total 931
telemt_me_idle_close_by_peer_total 931
telemt_me_route_drop_no_conn_total 523382
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1377841
telemt_me_endpoint_quarantine_total 939
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 920
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
telemt_me_writers_active_current 43
telemt_desync_total 9458
telemt_desync_full_logged_total 2714
telemt_desync_suppressed_total 6744
telemt_desync_frames_bucket_total{bucket="1_2"} 2806
telemt_desync_frames_bucket_total{bucket="3_10"} 3589
telemt_desync_frames_bucket_total{bucket="gt_10"} 3063
telemt_pool_swap_total 120
telemt_pool_force_close_total 3039
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 172
telemt_me_draining_writers_reap_progress_total 44614
telemt_me_writer_removed_unexpected_total 897
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3394
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42158
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2951
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41575
telemt_me_writer_teardown_success_total{mode="normal"} 45552
telemt_me_writer_teardown_noop_total 44618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90170
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.398613
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90170
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 172
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 803
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1373623
telemt_user_connections_current{user="hello"} 509
telemt_user_octets_from_client{user="hello"} 26231213749 (24.43 GB)
telemt_user_octets_to_client{user="hello"} 582860580979 (542.83 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 193244.8 (53h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13373082
telemt_connections_bad_total 1616795
telemt_connections_current 645
telemt_connections_me_current 645
telemt_handshake_timeouts_total 390383
telemt_upstream_connect_attempt_total 76819
telemt_upstream_connect_success_total 76465
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 76683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3043
telemt_me_reconnect_success_total 1523
telemt_me_reader_eof_total 1506
telemt_me_idle_close_by_peer_total 1506
telemt_me_route_drop_no_conn_total 4487568
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10073410
telemt_me_endpoint_quarantine_total 1399
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1464
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
telemt_desync_total 42240
telemt_desync_full_logged_total 13792
telemt_desync_suppressed_total 28448
telemt_desync_frames_bucket_total{bucket="1_2"} 10260
telemt_desync_frames_bucket_total{bucket="3_10"} 15517
telemt_desync_frames_bucket_total{bucket="gt_10"} 16463
telemt_pool_swap_total 214
telemt_pool_force_close_total 5656
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 682
telemt_me_draining_writers_reap_progress_total 69494
telemt_me_writer_removed_unexpected_total 1443
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5421
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65569
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5482
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63838
telemt_me_writer_teardown_success_total{mode="normal"} 70990
telemt_me_writer_teardown_noop_total 69496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 137867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 139594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140486
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.822870
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140486
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 682
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1336
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 10040095
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 194974249260 (181.58 GB)
telemt_user_octets_to_client{user="hello"} 4452471705076 (4.05 TB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 193241.2 (53h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11681314
telemt_connections_bad_total 1364860
telemt_connections_current 549
telemt_connections_me_current 549
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 312544
telemt_upstream_connect_attempt_total 104439
telemt_upstream_connect_success_total 103535
telemt_upstream_connect_fail_total 696
telemt_upstream_connect_attempts_per_request{bucket="1"} 104231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44224
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 696
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10671
telemt_me_reconnect_success_total 2634
telemt_me_reader_eof_total 2445
telemt_me_idle_close_by_peer_total 2444
telemt_me_seq_mismatch_total 102
telemt_me_route_drop_no_conn_total 5654918
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8987703
telemt_me_endpoint_quarantine_total 1582
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 53
telemt_me_single_endpoint_outage_exit_total 53
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 1467
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_me_writers_active_current 44
telemt_desync_total 41932
telemt_desync_full_logged_total 13504
telemt_desync_suppressed_total 28428
telemt_desync_frames_bucket_total{bucket="1_2"} 10838
telemt_desync_frames_bucket_total{bucket="3_10"} 15422
telemt_desync_frames_bucket_total{bucket="gt_10"} 15672
telemt_pool_swap_total 204
telemt_pool_force_close_total 5429
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 669
telemt_me_draining_writers_reap_progress_total 69628
telemt_me_writer_removed_unexpected_total 2486
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6812
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65392
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4958
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64199
telemt_me_writer_teardown_success_total{mode="normal"} 72204
telemt_me_writer_teardown_noop_total 69633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 139147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 140929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 141468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141837
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.502744
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141837
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 669
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 2115
telemt_me_writer_restored_fallback_total 137
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 8992273
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 157572999360 (146.75 GB)
telemt_user_octets_to_client{user="hello"} 3502128397690 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 77
```