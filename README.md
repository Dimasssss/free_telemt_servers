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

# Server Metrics 2026-03-23 06:01:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 118520.2 (32h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4225627
telemt_connections_bad_total 402112
telemt_connections_current 1705
telemt_connections_me_current 1705
telemt_handshake_timeouts_total 142572
telemt_upstream_connect_attempt_total 44064
telemt_upstream_connect_success_total 44063
telemt_upstream_connect_attempts_per_request{bucket="1"} 44063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28591
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 98
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 1547
telemt_me_reconnect_success_total 692
telemt_me_reader_eof_total 716
telemt_me_idle_close_by_peer_total 716
telemt_me_route_drop_no_conn_total 3465443
telemt_me_route_drop_channel_closed_total 1353
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3457753
telemt_me_writer_pick_total{mode="p2c",result="full"} 18
telemt_me_endpoint_quarantine_total 842
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 929
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
telemt_me_writers_active_current 46
telemt_desync_total 14360
telemt_desync_full_logged_total 4544
telemt_desync_suppressed_total 9816
telemt_desync_frames_bucket_total{bucket="1_2"} 3701
telemt_desync_frames_bucket_total{bucket="3_10"} 5369
telemt_desync_frames_bucket_total{bucket="gt_10"} 5290
telemt_pool_swap_total 131
telemt_pool_force_close_total 4009
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 760
telemt_me_draining_writers_reap_progress_total 40351
telemt_me_writer_removed_unexpected_total 688
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2899
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37740
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3941
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 68
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36342
telemt_me_writer_teardown_success_total{mode="normal"} 40639
telemt_me_writer_teardown_noop_total 40364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81003
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 440.343946
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81003
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 760
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 621
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 3445037
telemt_user_connections_current{user="hello"} 1705
telemt_user_octets_from_client{user="hello"} 46007944628 (42.85 GB)
telemt_user_octets_to_client{user="hello"} 903627134376 (841.57 GB)
telemt_user_unique_ips_current{user="hello"} 662
telemt_user_unique_ips_recent_window{user="hello"} 317
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 131885.9 (36h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4183029
telemt_connections_bad_total 388356
telemt_connections_current 717
telemt_connections_me_current 717
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 109720
telemt_upstream_connect_attempt_total 82170
telemt_upstream_connect_success_total 81186
telemt_upstream_connect_fail_total 872
telemt_upstream_connect_attempts_per_request{bucket="1"} 82058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 872
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 11020
telemt_me_reconnect_success_total 3967
telemt_me_reader_eof_total 3937
telemt_me_idle_close_by_peer_total 3936
telemt_me_route_drop_no_conn_total 3678461
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3317417
telemt_me_endpoint_quarantine_total 1074
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 55
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 55
telemt_me_single_endpoint_shadow_rotate_total 1039
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
telemt_desync_total 13647
telemt_desync_full_logged_total 7702
telemt_desync_suppressed_total 5945
telemt_desync_frames_bucket_total{bucket="1_2"} 3102
telemt_desync_frames_bucket_total{bucket="3_10"} 5347
telemt_desync_frames_bucket_total{bucket="gt_10"} 5198
telemt_pool_swap_total 124
telemt_pool_force_close_total 3464
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 272
telemt_me_draining_writers_reap_progress_total 55471
telemt_me_writer_removed_unexpected_total 3859
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6990
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52383
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2955
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 509
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52007
telemt_me_writer_teardown_success_total{mode="normal"} 59373
telemt_me_writer_teardown_noop_total 55472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114845
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.012391
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114845
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 272
telemt_me_refill_failed_total 279
telemt_me_writer_restored_same_endpoint_total 3513
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 3331826
telemt_user_connections_current{user="hello"} 717
telemt_user_octets_from_client{user="hello"} 44855788623 (41.78 GB)
telemt_user_octets_to_client{user="hello"} 842439034121 (784.58 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 426
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 206745.8 (57h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16741000
telemt_connections_bad_total 1697388
telemt_connections_current 2012
telemt_connections_me_current 2012
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 411624
telemt_upstream_connect_attempt_total 92750
telemt_upstream_connect_success_total 92638
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 92655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45828
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1733
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3272
telemt_me_reconnect_success_total 1700
telemt_me_reader_eof_total 1658
telemt_me_idle_close_by_peer_total 1655
telemt_me_route_drop_no_conn_total 14134353
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13298515
telemt_me_endpoint_quarantine_total 1405
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1566
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
telemt_me_writers_active_current 45
telemt_desync_total 55554
telemt_desync_full_logged_total 17756
telemt_desync_suppressed_total 37798
telemt_desync_frames_bucket_total{bucket="1_2"} 12378
telemt_desync_frames_bucket_total{bucket="3_10"} 21764
telemt_desync_frames_bucket_total{bucket="gt_10"} 21412
telemt_pool_swap_total 224
telemt_pool_force_close_total 7175
telemt_pool_stale_pick_total 20
telemt_me_writer_close_signal_drop_total 1108
telemt_me_draining_writers_reap_progress_total 71493
telemt_me_writer_removed_unexpected_total 1591
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5988
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66382
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6705
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64318
telemt_me_writer_teardown_success_total{mode="normal"} 72370
telemt_me_writer_teardown_noop_total 71547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143917
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 319.352566
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143917
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1108
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1471
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 13298293
telemt_user_connections_current{user="hello"} 2012
telemt_user_octets_from_client{user="hello"} 201211846593 (187.39 GB)
telemt_user_octets_to_client{user="hello"} 3617876138235 (3.29 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 737
telemt_user_unique_ips_recent_window{user="hello"} 345
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 206747.8 (57h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12228608
telemt_connections_bad_total 1299571
telemt_connections_current 1423
telemt_connections_me_current 1423
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 354808
telemt_upstream_connect_attempt_total 107206
telemt_upstream_connect_success_total 105791
telemt_upstream_connect_fail_total 901
telemt_upstream_connect_attempts_per_request{bucket="1"} 106692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45829
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3809
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 901
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4748
telemt_me_reconnect_success_total 2045
telemt_me_reader_eof_total 1904
telemt_me_idle_close_by_peer_total 1904
telemt_me_route_drop_no_conn_total 4621953
telemt_me_route_drop_channel_closed_total 505
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9041625
telemt_me_endpoint_quarantine_total 1411
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1583
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
telemt_me_writers_active_current 44
telemt_desync_total 39784
telemt_desync_full_logged_total 13448
telemt_desync_suppressed_total 26336
telemt_desync_frames_bucket_total{bucket="1_2"} 9861
telemt_desync_frames_bucket_total{bucket="3_10"} 15278
telemt_desync_frames_bucket_total{bucket="gt_10"} 14645
telemt_pool_swap_total 221
telemt_pool_force_close_total 6523
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 724
telemt_me_draining_writers_reap_progress_total 69637
telemt_me_writer_removed_unexpected_total 1934
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6099
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65335
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6010
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 513
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63114
telemt_me_writer_teardown_success_total{mode="normal"} 71434
telemt_me_writer_teardown_noop_total 69662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141096
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.728876
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141096
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 724
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1745
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8979145
telemt_user_connections_current{user="hello"} 1423
telemt_user_octets_from_client{user="hello"} 220797150140 (205.63 GB)
telemt_user_octets_to_client{user="hello"} 4043685779483 (3.68 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 547
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 206711.1 (57h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11373740
telemt_connections_bad_total 1045243
telemt_connections_current 1237
telemt_connections_me_current 1237
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 360963
telemt_upstream_connect_attempt_total 91621
telemt_upstream_connect_success_total 90042
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 90247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44412
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2377
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5921
telemt_me_reconnect_success_total 2500
telemt_me_reader_eof_total 2242
telemt_me_idle_close_by_peer_total 2241
telemt_me_route_drop_no_conn_total 5390758
telemt_me_route_drop_channel_closed_total 386
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8548750
telemt_me_endpoint_quarantine_total 1462
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1546
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 75
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
telemt_desync_total 38905
telemt_desync_full_logged_total 12919
telemt_desync_suppressed_total 25986
telemt_desync_frames_bucket_total{bucket="1_2"} 9819
telemt_desync_frames_bucket_total{bucket="3_10"} 14889
telemt_desync_frames_bucket_total{bucket="gt_10"} 14197
telemt_pool_swap_total 217
telemt_pool_force_close_total 6412
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 764
telemt_me_draining_writers_reap_progress_total 70251
telemt_me_writer_removed_unexpected_total 2387
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6841
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65734
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5838
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 574
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63839
telemt_me_writer_teardown_success_total{mode="normal"} 72575
telemt_me_writer_teardown_noop_total 70322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 137015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 139750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142897
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3175.292446
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142897
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 764
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2176
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8540500
telemt_user_connections_current{user="hello"} 1237
telemt_user_octets_from_client{user="hello"} 194531596231 (181.17 GB)
telemt_user_octets_to_client{user="hello"} 3543100197917 (3.22 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 76990.9 (21h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11773480
telemt_connections_bad_total 714341
telemt_connections_current 2338
telemt_connections_me_current 2338
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 325508
telemt_upstream_connect_attempt_total 68273
telemt_upstream_connect_success_total 64669
telemt_upstream_connect_fail_total 2323
telemt_upstream_connect_attempts_per_request{bucket="1"} 66992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6055
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2323
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8530
telemt_me_reconnect_success_total 1587
telemt_me_reader_eof_total 1007
telemt_me_idle_close_by_peer_total 1006
telemt_me_route_drop_no_conn_total 25404218
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9722997
telemt_me_endpoint_quarantine_total 613
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 213
telemt_me_single_endpoint_outage_reconnect_success_total 56
telemt_me_single_endpoint_quarantine_bypass_total 213
telemt_me_single_endpoint_shadow_rotate_total 619
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
telemt_me_writers_active_current 45
telemt_desync_total 17460
telemt_desync_full_logged_total 4901
telemt_desync_suppressed_total 12559
telemt_desync_frames_bucket_total{bucket="1_2"} 3377
telemt_desync_frames_bucket_total{bucket="3_10"} 7150
telemt_desync_frames_bucket_total{bucket="gt_10"} 6933
telemt_pool_swap_total 79
telemt_pool_force_close_total 2473
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 534
telemt_me_draining_writers_reap_progress_total 25557
telemt_me_writer_removed_unexpected_total 1463
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3292
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23681
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2126
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 347
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23084
telemt_me_writer_teardown_success_total{mode="normal"} 26973
telemt_me_writer_teardown_noop_total 25576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52549
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.190484
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52549
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 534
telemt_me_refill_failed_total 353
telemt_me_writer_restored_same_endpoint_total 1015
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 9750496
telemt_user_connections_current{user="hello"} 2338
telemt_user_octets_from_client{user="hello"} 91628092791 (85.34 GB)
telemt_user_octets_to_client{user="hello"} 752075330973 (700.42 GB)
telemt_user_msgs_from_client{user="hello"} 71666
telemt_user_msgs_to_client{user="hello"} 62721
telemt_user_unique_ips_current{user="hello"} 808
telemt_user_unique_ips_recent_window{user="hello"} 359
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 206717.6 (57h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11352899
telemt_connections_bad_total 997824
telemt_connections_current 1702
telemt_connections_me_current 1702
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 257806
telemt_upstream_connect_attempt_total 120675
telemt_upstream_connect_success_total 119391
telemt_upstream_connect_fail_total 1107
telemt_upstream_connect_attempts_per_request{bucket="1"} 120498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1381
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1107
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73708
telemt_me_reconnect_success_total 3310
telemt_me_reader_eof_total 2985
telemt_me_idle_close_by_peer_total 2982
telemt_me_route_drop_no_conn_total 5337369
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8936930
telemt_me_endpoint_quarantine_total 1418
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1574
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
telemt_desync_total 47532
telemt_desync_full_logged_total 16355
telemt_desync_suppressed_total 31177
telemt_desync_frames_bucket_total{bucket="1_2"} 9665
telemt_desync_frames_bucket_total{bucket="3_10"} 18225
telemt_desync_frames_bucket_total{bucket="gt_10"} 19642
telemt_pool_swap_total 213
telemt_pool_force_close_total 6123
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 74400
telemt_me_writer_removed_unexpected_total 3002
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7393
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70056
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5373
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 750
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68277
telemt_me_writer_teardown_success_total{mode="normal"} 77449
telemt_me_writer_teardown_noop_total 74401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 149684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 151114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 151533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 151806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 151840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 151843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 151843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 151846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 151850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 151850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 151850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 151850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 151850
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.393522
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 151850
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 4327
telemt_me_writer_restored_same_endpoint_total 2778
telemt_me_writer_restored_fallback_total 59
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7375
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 8939491
telemt_user_connections_current{user="hello"} 1702
telemt_user_octets_from_client{user="hello"} 199689572921 (185.98 GB)
telemt_user_octets_to_client{user="hello"} 3421873748904 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 635
telemt_user_unique_ips_recent_window{user="hello"} 294
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 143554.0 (39h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12153022
telemt_connections_bad_total 496328
telemt_connections_current 1160
telemt_connections_me_current 1160
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4901252
telemt_upstream_connect_attempt_total 69583
telemt_upstream_connect_success_total 69091
telemt_upstream_connect_fail_total 479
telemt_upstream_connect_attempts_per_request{bucket="1"} 69570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 479
telemt_me_reconnect_attempts_total 49412
telemt_me_reconnect_success_total 1980
telemt_me_reader_eof_total 1666
telemt_me_idle_close_by_peer_total 1665
telemt_me_route_drop_no_conn_total 4156828
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5840632
telemt_me_endpoint_quarantine_total 988
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1109
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32853
telemt_desync_full_logged_total 11259
telemt_desync_suppressed_total 21594
telemt_desync_frames_bucket_total{bucket="1_2"} 6603
telemt_desync_frames_bucket_total{bucket="3_10"} 12938
telemt_desync_frames_bucket_total{bucket="gt_10"} 13312
telemt_pool_swap_total 153
telemt_pool_force_close_total 4312
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 396
telemt_me_draining_writers_reap_progress_total 54321
telemt_me_writer_removed_unexpected_total 1703
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4292
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51790
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3868
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50009
telemt_me_writer_teardown_success_total{mode="normal"} 56082
telemt_me_writer_teardown_noop_total 54328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110410
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.921795
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110410
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 396
telemt_me_refill_failed_total 2755
telemt_me_writer_restored_same_endpoint_total 1749
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5832488
telemt_user_connections_current{user="hello"} 1160
telemt_user_octets_from_client{user="hello"} 122236089652 (113.84 GB)
telemt_user_octets_to_client{user="hello"} 2273269533086 (2.07 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 478
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 124524.7 (34h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1739394
telemt_connections_bad_total 37692
telemt_connections_current 1027
telemt_connections_me_current 1027
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 38421
telemt_upstream_connect_attempt_total 58489
telemt_upstream_connect_success_total 58294
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 58451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 858
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 2522
telemt_me_reconnect_success_total 1028
telemt_me_reader_eof_total 1024
telemt_me_idle_close_by_peer_total 1024
telemt_me_route_drop_no_conn_total 592982
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1544477
telemt_me_endpoint_quarantine_total 1061
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1027
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
telemt_me_writers_active_current 43
telemt_desync_total 10574
telemt_desync_full_logged_total 2986
telemt_desync_suppressed_total 7588
telemt_desync_frames_bucket_total{bucket="1_2"} 3351
telemt_desync_frames_bucket_total{bucket="3_10"} 3957
telemt_desync_frames_bucket_total{bucket="gt_10"} 3266
telemt_pool_swap_total 135
telemt_pool_force_close_total 3418
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 179
telemt_me_draining_writers_reap_progress_total 49913
telemt_me_writer_removed_unexpected_total 986
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3759
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47188
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3330
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46495
telemt_me_writer_teardown_success_total{mode="normal"} 50947
telemt_me_writer_teardown_noop_total 49917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100864
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.729159
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100864
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 179
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 882
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 1539988
telemt_user_connections_current{user="hello"} 1027
telemt_user_octets_from_client{user="hello"} 27945254697 (26.03 GB)
telemt_user_octets_to_client{user="hello"} 623014288847 (580.23 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 206722.3 (57h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13637543
telemt_connections_bad_total 1654700
telemt_connections_current 1631
telemt_connections_me_current 1631
telemt_handshake_timeouts_total 400121
telemt_upstream_connect_attempt_total 83400
telemt_upstream_connect_success_total 83031
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 83263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41841
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3290
telemt_me_reconnect_success_total 1636
telemt_me_reader_eof_total 1629
telemt_me_idle_close_by_peer_total 1629
telemt_me_route_drop_no_conn_total 4543540
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10280403
telemt_me_endpoint_quarantine_total 1534
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1573
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
telemt_me_writers_active_current 44
telemt_desync_total 43197
telemt_desync_full_logged_total 14092
telemt_desync_suppressed_total 29105
telemt_desync_frames_bucket_total{bucket="1_2"} 10510
telemt_desync_frames_bucket_total{bucket="3_10"} 15864
telemt_desync_frames_bucket_total{bucket="gt_10"} 16823
telemt_pool_swap_total 229
telemt_pool_force_close_total 5970
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 708
telemt_me_draining_writers_reap_progress_total 75510
telemt_me_writer_removed_unexpected_total 1557
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5791
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71338
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5796
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69540
telemt_me_writer_teardown_success_total{mode="normal"} 77129
telemt_me_writer_teardown_noop_total 75512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 149967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 151746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 152132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 152508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 152628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 152641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 152641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 152641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 152641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 152641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 152641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 152641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 152641
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.131701
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 152641
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 708
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 1438
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 10246775
telemt_user_connections_current{user="hello"} 1631
telemt_user_octets_from_client{user="hello"} 197418411092 (183.86 GB)
telemt_user_octets_to_client{user="hello"} 4571538467148 (4.16 TB)
telemt_user_unique_ips_current{user="hello"} 572
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 206718.8 (57h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11946051
telemt_connections_bad_total 1395972
telemt_connections_current 1493
telemt_connections_me_current 1493
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 321551
telemt_upstream_connect_attempt_total 111397
telemt_upstream_connect_success_total 110443
telemt_upstream_connect_fail_total 745
telemt_upstream_connect_attempts_per_request{bucket="1"} 111188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47510
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 745
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11149
telemt_me_reconnect_success_total 2778
telemt_me_reader_eof_total 2580
telemt_me_idle_close_by_peer_total 2579
telemt_me_seq_mismatch_total 112
telemt_me_route_drop_no_conn_total 5712415
telemt_me_route_drop_channel_closed_total 356
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9202159
telemt_me_endpoint_quarantine_total 1714
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1577
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
telemt_me_writers_active_current 42
telemt_desync_total 43147
telemt_desync_full_logged_total 13802
telemt_desync_suppressed_total 29345
telemt_desync_frames_bucket_total{bucket="1_2"} 11188
telemt_desync_frames_bucket_total{bucket="3_10"} 15937
telemt_desync_frames_bucket_total{bucket="gt_10"} 16022
telemt_pool_swap_total 219
telemt_pool_force_close_total 5710
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 75983
telemt_me_writer_removed_unexpected_total 2618
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7214
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71490
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 70273
telemt_me_writer_teardown_success_total{mode="normal"} 78704
telemt_me_writer_teardown_noop_total 75988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 151948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 153769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 154323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 154642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 154692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 154692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 154692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 154692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 154692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 154692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 154692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 154692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 154692
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.859968
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 154692
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 435
telemt_me_writer_restored_same_endpoint_total 2213
telemt_me_writer_restored_fallback_total 147
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 9206439
telemt_user_connections_current{user="hello"} 1493
telemt_user_octets_from_client{user="hello"} 160090006396 (149.10 GB)
telemt_user_octets_to_client{user="hello"} 3602568232954 (3.28 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 521
telemt_user_unique_ips_recent_window{user="hello"} 211
```